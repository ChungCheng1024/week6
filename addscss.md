🎨 樣式設計對照表
1️⃣ 間距（Spacing Utilities）

來自 $spacers

$spacer: 1rem; // 16px

class	px 值	說明
m-0	0px	    margin:0
m-1	4px	    margin:4px
m-2	8px	    margin:8px
m-3	12px	margin:12px
m-4	16px	margin:16px
m-5	24px	margin:24px
m-6	40px	margin:40px
m-7	48px	margin:48px
m-8	80px	margin:80px

👉 p-* / mt-* / mb-* / ms-* / me-* 全部同樣對應。

2️⃣ 字體大小（Font Sizes）

來自 $font-sizes

class	px 值	說明
fs-1	48px	h1
fs-2	32px	h2
fs-3	28px	h3
fs-4	24px	h4
fs-5	18px	h5
fs-6	16px	h6
fs-7	80px	你新增的
3️⃣ 字重（Font Weight）

來自 $font-weight-*

class	weight
fw-light	300
fw-normal	400
fw-medium	500
fw-semibold	600
fw-bold	700
4️⃣ 顏色（Colors & Theme）

你自訂的 $theme-colors

class	hex 值
bg-white	#FCFCFD
bg-natural-95	#F0F3F5
bg-natural-90	#E0E5EB
bg-natural-85	#D1D9E1
bg-natural-75	#B2BFCC
bg-natural-60	#8599AD
bg-natural-50	#667F99
bg-natural-30	#3D4D5C
bg-natural-10	#141A1F
bg-primary-97	#F1F4FD
bg-primary-90	#D2D9F9
bg-primary-80	#A4B4F3
bg-primary-70	#778EEE
bg-primary-60	#4A69E8
bg-primary-40	#1736B5
bg-primary-25	#0E2271
bg-secondary-90	#D7F4EC
bg-secondary-70	#87DEC5
bg-secondary-50	#36C99F
bg-secondary-35	#268C6F

👉 對應 text-* 與 border-* 都能用，例如 text-primary-60、border-natural-85。

5️⃣ 圓角（Border Radius）

來自 $border-radius

class	px 值
rounded	16px
rounded-sm	12px
rounded-lg	8px
rounded-xl	16px
rounded-xxl	32px
rounded-pill	9999px (全圓)
6️⃣ 陰影（Box Shadow）

來自 $box-shadow

class	效果
shadow-sm	小陰影
shadow	0 0 1rem rgba(0,0,0,.12)
shadow-lg	大陰影
7️⃣ 邊框（Borders）

border = 1px 實線

border-0 移除邊框

border-natural-85 = #D1D9E1

8️⃣ Flex & 對齊

d-flex, flex-column, flex-row

justify-content-start|center|end|between|around

align-items-start|center|end

9️⃣ 文字排版

text-start / text-center / text-end

lh-1（行高=1，收緊行距）

lh-base（行高=1.5，預設）

lh-lg（行高=2）