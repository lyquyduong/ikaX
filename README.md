# IkaX — Feature List / Danh sách tính năng / 功能列表

> IkaX is a free, open-source Manifest V3 Chrome extension that enhances the Ikariam browser game. Forked from IkaEasy V3 with continued development and new features.

---

## Table of Contents

- [English](#english)
- [Tiếng Việt](#tiếng-việt)
- [中文](#中文)

---

<a id="english"></a>
## English

### 1. Empire Manager

A comprehensive cross-city management dashboard accessible from the left menu.

#### 1.1 Resources Tab
- View all resource stocks (wood, wine, marble, crystal, sulfur) across every city in one table
- Hourly and daily production rates
- Storage capacity and warehouse safe limits
- Expense tracking per hour, day, week, and month
- Wine depletion countdown timer
- Corruption percentage per city
- Research stats (scientists, research points, form of government)
- Population satisfaction and growth rates
- **Bulk Set Production** — set wood and luxury workers for all cities at once, with overcharge option
- **Bulk Set Scientists** — maximize scientists in every city with one click
- Inline worker input per city with apply button
- Auto-refresh with configurable interval (60–3600 seconds)
- Pause/resume auto-refresh toggle
- Premium account notice (storage & theft security)

#### 1.2 Buildings Tab
- Building levels for all cities displayed in a grid
- One-click upgrade and demolish from the dashboard
- Open building in city directly
- Hide fully-leveled buildings (level ≥ 50) toggle
- Visual indicator for buildings under construction
- Cost-to-next-level and resource difference display

#### 1.3 Espionage Tab
- Hideout levels across all cities
- Spy counts: total, max, in defence, on mission, in training
- **Bulk Train All** — queue maximum trainable spies in every city with free slots
- Individual train button per city
- Status indicators: Full, Expanding, In Training
- Auto-refresh with configurable interval
- Last sync timestamp

#### 1.4 Military Tab
- Army units and ships displayed per city in a grid (all unit types: Hoplite, Steam Giant, Spearman, Swordsman, Slinger, Archer, Gunner, Ram, Catapult, Mortar, Gyrocopter, Bombardier, Cook, Doctor, Spartan + all ship types)
- Recruit units directly from the dashboard with a cost calculator
- Build queue status per city (queue slots used)
- Barracks and shipyard level awareness
- Auto-refresh with configurable interval
- Sync button to manually fetch latest data
- Last sync timestamp
- Collapsible army/navy sections

### 2. Building Queue

- Queue multiple building upgrades across different cities
- Automatic construction start when current building finishes
- Cross-city queuing: automatically switches to the target city
- Warning countdown before construction starts (with snooze option: "Snooze for 1 minute")
- Add-to-queue button on building tooltips
- **Note:** Works only while the game tab is open in the browser

### 3. City View Enhancements

- **Building levels** — circular badges showing current level on each building
- **Quick-start tooltip** — hover over a building to see upgrade cost and start construction
- **Resource production rate** — hourly production shown next to each resource bar
- **Gold income summary** — net gold per hour displayed on the gold bar (green = positive, red = negative)
- **Wine depletion timer** — "Left for X days" shown when wine consumption exceeds production
- **Quick city switch** — arrow button to cycle through cities
- **City hotkeys** — switch cities using keyboard keys 0–9, -, =
- **Resource details** — per-day, per-week, per-month breakdowns in tooltips
- **Prevent colony demolition** — safety lock blocks accidental destruction of non-mobile colonies with a warning prompt

### 4. Island View

- **Action Points** — shows AP count on the island
- **Ship ownership** — displays who owns ships docked at the island
- **Resource levels** — wood, mine, and wonder levels shown directly on the island map with circular badges
- **Detailed city info** — expanded information for each city on the island
- **Alliance/player color markers** — cities colored by alliance or player marking (see section 6)

### 5. World Map & Island Search

- **Island search panel** — search and filter islands on the world map
- **Filter by resource type** — wood, wine, marble, crystal, sulfur
- **Filter by wonder type**
- **Occupancy filter** — find empty or full islands
- **Restart search** — quickly reset filters

### 6. Alliance & Player Marking

- **Alliance markers** — assign colors to alliances; all their cities are highlighted on the island view
- **Player markers** — assign colors to individual players
- **Persistent markers** — saved to local storage, survive page reloads
- **Easy management** — dedicated window for adding/editing/removing markers

### 7. Military Advisor Enhancements

- **Fleet composition** — shows detailed unit breakdown in the troop movements window (transport, plunder, army deployment, navy deployment)
- **Combat report saving** — save battle reports to ikalogs.ru for analysis
- **Report types** — full log, short log, last round, every N rounds, specific rounds
- **Round-by-round analysis** — resource losses, score changes, attacker vs defender breakdown
- **Combat report links** — quick link to last saved report

### 8. Diplomacy Enhancements

- **Clickable links** — URLs in messages become clickable; image links (clip2net) auto-embed as inline previews
- **Alliance member list** — new tab in Diplomatic Advisor showing all alliance members
- **Tab renaming** — clearer tab labels (Messages, Agora, Treaty, Board, Alliance)
- **Premium button hiding** — hides Ambrosia prompts in the diplomacy view

### 9. Transport & Trade

- **Quick-load resource buttons** — ±500, +1000, +2000, +5000 buttons for fast resource loading
- **Unit load buttons** — All / Half / Nothing buttons for loading units onto ships
- **Movement tracking** — transport missions tracked and displayed in the military advisor

### 10. Barbarian Village

- **Loot calculator** — shows total resources available to rob
- **Ship calculator** — calculates how many merchant ships you need

### 11. Spy (Safehouse) Report

- **Enhanced spy reports** — warehouse level, idle status, resources available to steal
- **Ship calculation** — shows how many ships needed to transport stolen resources

### 12. Desktop Notifications

- **Building upgrade complete** — notifies when a building finishes upgrading
- **Building upgrade soon** — early warning before completion
- **Unit/ship recruitment complete** — notifies when unit training finishes
- **Transport loaded** — when a transport mission finishes loading
- **Transport arrived** — when a transport reaches its destination
- **Transport returned** — when ships return home
- **Advisor alerts** — diplomatic, military, mayor, research advisor activity
- **Auto-hide** — notifications dismiss automatically (configurable)

### 13. Notes

- Personal notes system accessible from the toolbar
- Create, edit, and delete notes
- Notes stored locally in the browser (per server)
- System note protection (cannot accidentally modify game notes)

### 14. Quality of Life

- **Hide Premium** — removes premium/Ambrosia prompts throughout the game
- **Hide ads** — removes advertisement banners
- **Hide Happy Hour** — hides the Happy Hour notification bar
- **Hide friends bar** — hides the social friends bar
- **Auto-accept daily bonus** — automatically submits the daily reward form
- **Quick menu** — removes animation from the left-side menu for faster access
- **Toolbar popup** — click the extension icon to see gold balance, income breakdown, and empire-wide resource totals without opening the game

### 15. Improvements over IkaEasy V3

- **Manifest V3** — fully migrated to Chrome's latest extension platform (Manifest V3)
- **Empire Manager: Espionage tab** — NEW: monitor spies, bulk train across all cities
- **Empire Manager: Military tab** — NEW: view units/ships, recruit from dashboard, build queue tracking
- **Empire Manager: Bulk workers** — NEW: set production workers or scientists across all cities in one click
- **Empire Manager: Auto-refresh** — NEW: configurable auto-refresh intervals for Resources, Espionage, and Military tabs
- **Empire Manager: Workers input** — NEW: inline worker input with per-city apply
- **Toolbar popup** — NEW: gold overview and empire resources at a glance from the browser toolbar
- **Buy Me a Coffee** — donation system replaced from Patreon to Buy Me a Coffee
- **GitHub support** — bug reporting and feature requests via GitHub Issues
- **Build system** — automated build script for Chrome Web Store packaging
- **Performance & stability** — various bug fixes and code modernization
- **Safety lock** — prevent accidental colony demolition for non-mobile colonies
- **Enhanced combat reports** — resource and score difference breakdown

---

<a id="tiếng-việt"></a>
## Tiếng Việt

### 1. Quản lý Đế chế (Empire Manager)

Bảng điều khiển quản lý đa thành phố, truy cập từ menu bên trái.

#### 1.1 Tab Tài nguyên
- Xem tất cả tài nguyên (gỗ, rượu, đá cẩm thạch, pha lê, lưu huỳnh) của mọi thành phố trong một bảng
- Tốc độ sản xuất theo giờ và theo ngày
- Dung lượng kho và giới hạn an toàn
- Theo dõi chi phí theo giờ, ngày, tuần và tháng
- Đếm ngược thời gian hết rượu
- Tỷ lệ tham nhũng mỗi thành phố
- Thống kê nghiên cứu (nhà khoa học, điểm nghiên cứu, hình thức chính quyền)
- Mức độ hài lòng và tốc độ tăng trưởng dân số
- **Thiết lập sản xuất hàng loạt** — đặt công nhân gỗ và xa xỉ cho tất cả thành phố cùng lúc, có tùy chọn quá tải
- **Thiết lập nhà khoa học hàng loạt** — tối đa hóa nhà khoa học ở mọi thành phố chỉ bằng một cú nhấp
- Nhập số lượng công nhân trực tiếp cho từng thành phố
- Tự động làm mới với khoảng thời gian tùy chỉnh (60–3600 giây)
- Tạm dừng/tiếp tục tự động làm mới

#### 1.2 Tab Công trình
- Cấp độ công trình của tất cả thành phố hiển thị dạng lưới
- Nâng cấp và phá hủy một cú nhấp từ bảng điều khiển
- Mở công trình trong thành phố trực tiếp
- Ẩn công trình đã đạt cấp tối đa (≥ 50)
- Hiển thị chi phí nâng cấp và chênh lệch tài nguyên

#### 1.3 Tab Gián điệp
- Cấp độ Sào huyệt ở tất cả thành phố
- Số lượng gián điệp: tổng, tối đa, phòng thủ, nhiệm vụ, đang huấn luyện
- **Huấn luyện tất cả** — xếp hàng huấn luyện gián điệp tối đa ở mọi thành phố còn chỗ trống
- Nút huấn luyện riêng cho từng thành phố
- Trạng thái: Đầy, Đang mở rộng, Đang huấn luyện
- Tự động làm mới với khoảng thời gian tùy chỉnh

#### 1.4 Tab Quân sự
- Quân đội và tàu hiển thị theo từng thành phố (tất cả loại đơn vị)
- Tuyển quân trực tiếp từ bảng điều khiển với máy tính chi phí
- Trạng thái hàng đợi xây dựng mỗi thành phố
- Tự động làm mới với khoảng thời gian tùy chỉnh
- Nút đồng bộ thủ công

### 2. Hàng đợi Xây dựng

- Xếp hàng nhiều nâng cấp công trình ở các thành phố khác nhau
- Tự động bắt đầu xây dựng tiếp theo khi hoàn thành
- Xếp hàng xuyên thành phố: tự động chuyển sang thành phố mục tiêu
- Cảnh báo đếm ngược trước khi xây dựng (có tùy chọn hoãn 1 phút)
- **Lưu ý:** Chỉ hoạt động khi tab game đang mở

### 3. Cải tiến Giao diện Thành phố

- **Cấp độ công trình** — huy hiệu tròn hiển thị cấp độ trên mỗi công trình
- **Tooltip nhanh** — di chuột để xem chi phí nâng cấp và bắt đầu xây dựng
- **Tốc độ sản xuất** — sản xuất theo giờ hiển thị bên cạnh mỗi thanh tài nguyên
- **Tóm tắt vàng** — thu nhập ròng vàng mỗi giờ (xanh = dương, đỏ = âm)
- **Đếm ngược rượu** — "Còn lại X ngày" khi tiêu thụ vượt sản xuất
- **Chuyển thành phố nhanh** — nút mũi tên để duyệt qua các thành phố
- **Phím tắt thành phố** — chuyển thành phố bằng phím 0–9, -, =
- **Chống phá hủy thuộc địa** — khóa an toàn ngăn xóa nhầm thuộc địa cố định

### 4. Giao diện Đảo

- Hiển thị Điểm Hành động (AP)
- Thông tin chủ sở hữu tàu
- Cấp độ gỗ, mỏ và kỳ quan hiển thị trực tiếp trên bản đồ đảo
- Thông tin chi tiết từng thành phố trên đảo
- Đánh dấu màu liên minh/người chơi

### 5. Bản đồ Thế giới & Tìm kiếm Đảo

- Bảng tìm kiếm đảo trên bản đồ thế giới
- Lọc theo loại tài nguyên, loại kỳ quan
- Lọc theo mức độ chiếm đóng (trống/đầy)
- Đặt lại tìm kiếm nhanh

### 6. Đánh dấu Liên minh & Người chơi

- Gán màu cho liên minh và người chơi
- Các thành phố được tô màu trên giao diện đảo
- Lưu trữ cục bộ, không mất khi tải lại trang

### 7. Cải tiến Cố vấn Quân sự

- Hiển thị thành phần đội quân trong cửa sổ di chuyển
- Lưu báo cáo chiến đấu lên ikalogs.ru
- Phân tích chi tiết theo từng vòng

### 8. Cải tiến Ngoại giao

- Link trong tin nhắn có thể nhấp; link hình ảnh tự động nhúng
- Tab danh sách thành viên liên minh
- Đổi tên tab rõ ràng hơn

### 9. Vận chuyển & Thương mại

- Nút tải nhanh tài nguyên (±500, +1000, +2000, +5000)
- Nút tải đơn vị (Tất cả / Một nửa / Không)

### 10. Làng Barbarian

- Tính toán tổng tài nguyên có thể cướp
- Tính số tàu buôn cần thiết

### 11. Báo cáo Gián điệp (Sào huyệt)

- Cấp độ kho, trạng thái rảnh, tài nguyên có thể ăn cắp
- Tính số tàu cần để vận chuyển

### 12. Thông báo Desktop

- Hoàn thành nâng cấp công trình
- Cảnh báo sắp hoàn thành
- Hoàn thành tuyển quân/đóng tàu
- Vận chuyển đã tải / đã đến / đã trở về
- Cảnh báo cố vấn
- Tự động ẩn (tùy chỉnh)

### 13. Ghi chú

- Hệ thống ghi chú cá nhân từ thanh công cụ
- Tạo, sửa, xóa ghi chú
- Lưu trữ cục bộ trong trình duyệt

### 14. Tiện ích

- Ẩn Premium / quảng cáo / Happy Hour / thanh bạn bè
- Tự động nhận thưởng hàng ngày
- Menu nhanh (bỏ hiệu ứng hoạt hình)
- Popup thanh công cụ xem nhanh vàng và tài nguyên

### 15. Cải tiến so với IkaEasy V3

- **Manifest V3** — di chuyển hoàn toàn sang nền tảng extension mới nhất
- **Tab Gián điệp** — MỚI: giám sát gián điệp, huấn luyện hàng loạt
- **Tab Quân sự** — MỚI: xem đơn vị/tàu, tuyển quân từ bảng điều khiển
- **Công nhân hàng loạt** — MỚI: thiết lập sản xuất hoặc nhà khoa học cho tất cả thành phố
- **Tự động làm mới** — MỚI: khoảng thời gian làm mới tùy chỉnh
- **Popup thanh công cụ** — MỚI: tổng quan vàng và tài nguyên từ thanh trình duyệt
- **Hỗ trợ GitHub** — báo lỗi và yêu cầu tính năng qua GitHub Issues
- **Khóa an toàn** — ngăn phá hủy thuộc địa nhầm

---

<a id="中文"></a>
## 中文

### 1. 帝国管理器 (Empire Manager)

从左侧菜单进入的跨城市综合管理面板。

#### 1.1 资源选项卡
- 在一个表格中查看所有城市的资源（木材、葡萄酒、大理石、水晶、硫磺）
- 每小时和每日产量
- 仓库容量和安全上限
- 按小时、日、周、月追踪开支
- 葡萄酒耗尽倒计时
- 每个城市的腐败率
- 研究统计（科学家、研究点数、政体形式）
- 人口满意度和增长率
- **批量设置生产** — 一键为所有城市设置木材和奢侈品工人，可选择超载模式
- **批量设置科学家** — 一键最大化所有城市的科学家
- 每个城市可单独输入工人数量
- 可配置的自动刷新间隔（60–3600 秒）
- 暂停/恢复自动刷新

#### 1.2 建筑选项卡
- 所有城市的建筑等级以网格形式显示
- 从面板一键升级和拆除
- 直接在城市中打开建筑
- 隐藏已满级建筑（≥ 50 级）
- 显示升级费用和资源差异

#### 1.3 间谍选项卡
- 所有城市的藏身处等级
- 间谍数量：总数、上限、防御中、执行任务中、训练中
- **全部训练** — 为所有有空位的城市排队训练最大数量间谍
- 每个城市单独的训练按钮
- 状态指示：满员、扩建中、训练中
- 可配置的自动刷新间隔

#### 1.4 军事选项卡
- 按城市显示陆军单位和船只（所有单位类型）
- 直接从面板招募单位，附带费用计算器
- 每个城市的建造队列状态
- 可配置的自动刷新间隔
- 手动同步按钮

### 2. 建造队列

- 跨城市排队多个建筑升级
- 当前建筑完成后自动开始下一个
- 跨城市排队：自动切换到目标城市
- 建造前倒计时警告（可延迟 1 分钟）
- **注意：** 仅在游戏标签页打开时有效

### 3. 城市视图增强

- **建筑等级** — 每个建筑上显示圆形等级标志
- **快速提示** — 悬停查看升级费用并开始建造
- **资源产量** — 每个资源栏旁显示每小时产量
- **黄金摘要** — 金条上显示每小时净黄金收入（绿色=正、红色=负）
- **葡萄酒倒计时** — 消耗超过产量时显示"剩余 X 天"
- **快速切换城市** — 箭头按钮循环切换城市
- **城市快捷键** — 使用键盘 0–9、-、= 切换城市
- **防止殖民地拆除** — 安全锁阻止意外销毁非移动殖民地

### 4. 岛屿视图

- 显示行动点 (AP)
- 船只所有者信息
- 木材、矿山和奇迹等级直接显示在岛屿地图上
- 岛上每个城市的详细信息
- 联盟/玩家颜色标记

### 5. 世界地图与岛屿搜索

- 世界地图上的岛屿搜索面板
- 按资源类型、奇迹类型筛选
- 按占用率筛选（空岛/满岛）
- 快速重置搜索

### 6. 联盟与玩家标记

- 为联盟和玩家分配颜色
- 城市在岛屿视图中按颜色高亮显示
- 本地存储，页面刷新不丢失

### 7. 军事顾问增强

- 部队移动窗口显示详细兵种组成
- 保存战斗报告至 ikalogs.ru
- 逐回合详细分析

### 8. 外交增强

- 消息中的链接可点击；图片链接自动内嵌预览
- 外交顾问中新增联盟成员列表选项卡
- 更清晰的选项卡名称

### 9. 运输与贸易

- 快速装载资源按钮（±500、+1000、+2000、+5000）
- 单位装载按钮（全部/一半/无）

### 10. 野蛮人村庄

- 计算可抢夺的总资源
- 计算所需商船数量

### 11. 间谍报告（藏身处）

- 仓库等级、闲置状态、可窃取资源
- 计算运输所需船只数量

### 12. 桌面通知

- 建筑升级完成
- 即将完成预警
- 单位/船只招募完成
- 运输已装载/已到达/已返回
- 顾问活动提醒
- 自动隐藏（可配置）

### 13. 笔记

- 从工具栏访问的个人笔记系统
- 创建、编辑、删除笔记
- 本地浏览器存储

### 14. 便利功能

- 隐藏高级会员/广告/欢乐时光/好友栏
- 自动领取每日奖励
- 快速菜单（去除动画效果）
- 工具栏弹窗快速查看黄金和资源

### 15. 相比 IkaEasy V3 的改进

- **Manifest V3** — 完全迁移至 Chrome 最新扩展平台
- **间谍选项卡** — 新增：监控间谍、批量训练
- **军事选项卡** — 新增：查看单位/船只、从面板招募
- **批量工人设置** — 新增：一键设置所有城市的生产或科学家
- **自动刷新** — 新增：可配置的刷新间隔
- **工具栏弹窗** — 新增：从浏览器工具栏快速查看黄金和资源概览
- **GitHub 支持** — 通过 GitHub Issues 报告错误和请求功能
- **安全锁** — 防止意外拆除殖民地

---

## Links

- **GitHub:** https://github.com/lyquyduong/ikaX
- **Bug Reports:** https://github.com/lyquyduong/ikaX/issues
- **Support:** https://www.buymeacoffee.com/ikax
