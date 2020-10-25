### Design draft description:
1. The design draft is divided into the head, the banner in the middle, the main navigation, the content area, and the bottom
2. The head area is a 100% wide dark background, and there is a 960px fixed-width centered area in the middle of the head, which includes the left logo and the upper right corner navigation
3. Banner is a 100% wide block. There is an example of the current picture numbers displayed by the banner in the lower right part of the middle. The number corresponding to the picture being displayed has a special style (note that there is no need to implement the business logic of the banner display, just follow the design draft Do static style)
4. The main navigation area has a 100% wide gray line. Above the line, the 960px area in the middle is the navigation menu. The menu corresponding to the page currently being browsed has a special style.
5. The main content area, the width is 960px, each content inside has at least 80px padding, the width of each content is adaptive, you can use flex layout

Chinese version:
### 设计稿描述：
1. 设计稿分为头部，中间的Banner，主导航，内容区域，底部
2. 头部区域为100%宽的一个深色背景，头部中间有一块960px的定宽居中区域，里面包括了左边的Logo和右上角导航
3. Banner为100%宽的区块，中间右下方有banner轮显的当前图片数字的示例，其中正在显示的图片对应的数字有特殊样式（注意不需要实现轮显banner的业务逻辑，只是按照设计稿做静态样式）
4. 主导航区域，有一个100%宽的灰色线条，线条之上，在中间960px区域是导航菜单，当前正在浏览页对应的菜单有特殊样式
5. 主要内容区域，宽度为960px，里面每个内容都有至少80px的padding，每一个内容的宽度均为自适应，可以使用flex布局