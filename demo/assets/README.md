# 资源图投放指南（按页分类版）

每一页有它自己的文件夹，切好的素材丢进对应文件夹即可。**不用想"这张属于哪个类别"，跟着视觉稿走就行。**

## 文件夹 vs 视觉稿整图对照

| 整图（已存在，别动） | 对应的切图文件夹 |
|---|---|
| `01_select_team.png` | `01_select_team/` |
| `02_select_player.png` | `02_select_player/` |
| `03_training_lineup.png` | `03_training_lineup/` |
| `04_training_task.png` | `04_training_task/` |
| `05_training_rank.png` | `05_training_rank/` |
| `06_shop.png` | `06_shop/` |
| `07_exchange_shop.png` | `07_exchange_shop/` |
| `08_popup_star_complete.png` | `08_popup_star/` |
| `09_popup_nurture_success.png` | `09_popup_success/` |
| `10_popup_all_teams.png` | `10_popup_all_teams/` |
| — | `common/` ← 跨页面通用元素（Header、品牌 Logo 等） |

## 每页建议切什么

### 01_select_team/（选择球队页）
```
01_select_team/
├── team-01.png ~ team-10.png     球队卡主视觉（或 chelsea.png / manchester-city.png…）
├── btn-select-default.png        "选择"按钮默认态
├── btn-select-disabled.png       置灰态
├── btn-select-hover.png          hover 态（可选）
└── bg.jpg                        背景（可选，如果要替换）
```

### 02_select_player/（选择球员页）
```
02_select_player/
├── field.png                     足球场俯视图（阵形底图）
├── player-01.png ~ player-15.png 球员卡（含底框）
├── position-slot.png             阵位空槽
├── position-slot-active.png      阵位激活态
├── formation-label.png           "阵容 4-2-2-1-1"标签
└── btn-start.png                 "开始冠军之路"按钮
```

### 03_training_lineup/（球队养成室 · 阵容）
```
03_training_lineup/
├── team-info-card.png            左侧球队信息卡
├── star-1.png ~ star-5.png       星级进度图标
├── field-lineup.png              中央阵容可视化
├── player-mini.png               场上的小球员卡
├── grade-badge-sss.png           段位徽章 SSS/SS/S/A/B
├── grade-badge-ss.png
├── grade-badge-s.png
├── grade-badge-a.png
├── grade-badge-b.png
├── btn-reselect.png              "重新选择"按钮
├── btn-edit.png                  "编辑阵容"按钮
└── btn-all-teams.png             "所有球队"按钮
```

### 04_training_task/（任务 Tab）
```
04_training_task/
├── task-card-default.png         任务卡底图
├── task-card-claimable.png       可领取态
├── task-card-done.png            已领取态
├── task-card-bonus.png           增益领取态
├── btn-claim.png                 "领取"按钮
├── btn-claim-all.png             "一键领取"按钮
├── btn-go.png                    "去完成"按钮
├── progress-bar.png              进度条底
├── point-icon.png                积分图标
└── reward-box.png                奖励图标（如球员包）
```

### 05_training_rank/（排行榜）
```
05_training_rank/
├── rank-row-default.png          榜单行底
├── rank-row-mine.png             "我"行（悬浮底部）
├── rank-crown-gold.png           第 1 名皇冠
├── rank-crown-silver.png         第 2 名
├── rank-crown-bronze.png         第 3 名
├── tab-personal.png              "个人排行"胶囊
├── tab-team.png                  "阵容排行"胶囊
├── reward-box.png                夺冠奖励图
└── btn-rule.png                  "排行规则说明"按钮
```

### 06_shop/（真金商店）
```
06_shop/
├── item-pack-legend.png          传奇球员包
├── item-pack-normal.png
├── item-coin.png                 金币道具
├── item-ticket.png
├── price-tag.png                 价格标签底
├── badge-sold-out.png            "已售罄"角标
├── badge-limit.png               "每周/每日限量"标签
└── btn-record.png                "购买记录"入口
```

### 07_exchange_shop/（积分兑换）
```
07_exchange_shop/
├── item-legend.png               传奇兑换道具
├── item-segment.png              段位卡
├── point-icon.png                积分图标（大）
└── btn-exchange-record.png       "兑换记录"入口
```

### 08_popup_star/（星级达成弹窗）
```
08_popup_star/
├── popup-bg.png                  弹窗主背景
├── star-burst.png                星星光爆
├── reward-player-pack.png        获得的球员包
├── text-congrats.png             "恭喜"大字
└── btn-confirm.png               "确认"按钮
```

### 09_popup_success/（养成成功弹窗）
```
09_popup_success/
├── popup-bg.png                  弹窗背景
├── trophy.png                    奖杯图
├── confetti.png                  彩带粒子（可多张）
├── btn-confirm.png               "确认"
└── btn-cancel.png                "取消"
```

### 10_popup_all_teams/（所有球队弹窗）
```
10_popup_all_teams/
├── team-grid-card.png            小尺寸球队卡模板
├── team-01.png ~ team-30.png     30 支球队（也可以 01_select_team 里复用）
├── star-small.png                小星级图标
└── btn-close.png                 关闭按钮
```

### common/（跨页面通用）
```
common/
├── logo-fconline.png             FCONLINE 品牌标
├── logo-fc26.png                 FC26 OUT NOW 角标
├── logo-activity.png             活动 Logo
├── header-bg.png                 顶部导航条背景
├── icon-back.svg                 返回箭头
├── icon-close.svg                × 关闭
├── icon-coin.png                 金币图标（Header 显示用）
├── icon-point.png                积分图标
├── avatar-default.png            默认用户头像
└── font/                         字体文件（如果要打包）
```

## 命名规则（越简单越好）

- **小写英文 + 连字符**（推荐）：`btn-select.png`、`team-chelsea.png`
- **或纯编号**（最省事）：`team-01.png` ~ `team-30.png`、`player-01.png` ~ `player-15.png`
- **别用中文命名**（跨平台可能乱码）
- **透明背景**：导出前检查无白色矩形底

## 交付节奏（最灵活）

你切完一页就说一声：

> "01 选球队页切好了"  
> "03 养成室页的段位徽章 + 按钮丢进去了"  
> "common 里加了 fconline logo"

我看到就**把 Demo 里对应页**从"一整张 PNG"升级成"背景 + 独立可交互的卡片/按钮"。

## 推荐切的顺序

**按评审收益排**：

1. 🔴 **common/** 先切 FCONLINE + FC26 logo → 所有页立刻显品牌
2. 🔴 **01_select_team/** 10 支球队 Logo → 选队页立刻活
3. 🟡 **03_training_lineup/** 段位徽章 + 星级 → 养成页活
4. 🟡 **04_training_task/** 按钮态 → 任务交互完整
5. 🟢 **08/09/10 弹窗/** → 弹窗微动效
6. 🟢 其他

## 如果某页你切烦了

直接告诉我：

> "02 页我不切了，让你扒"

我用 Figma API 帮你批量扒（需要你给我 Figma 里那页对应组件的节点 ID 或帧名）。

## 我会做什么

你每丢进一批 → 告诉我 → 我做三件事：
1. **验收**：ls 看文件夹，确认没损坏
2. **接代码**：把热区 Demo 里对应位置换成真的 `<img>` 卡片
3. **更新 README**：标记这一页的切图完成度

轻松点，一步步来 👌
