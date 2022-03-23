- [应用开发导读](application-dev-guide.md)
- 快速开始
  - 应用开发快速入门
    - DevEco Studio（OpenHarmony）使用指南
      - [概述](quick-start/deveco-studio-overview.md)
      - [版本变更说明](quick-start/deveco-studio-release-notes.md)
      - [配置OpenHarmony SDK](quick-start/configuring-openharmony-sdk.md)
      - 创建OpenHarmony工程
        - [使用工程向导创建新工程](quick-start/use-wizard-to-create-project.md)
        - [通过导入Sample方式创建新工程](quick-start/import-sample-to-create-project.md)
      - [配置OpenHarmony应用签名信息](quick-start/configuring-openharmony-app-signature.md)
      - [安装运行OpenHarmony应用](quick-start/installing-openharmony-app.md)
    - 快速入门
      - [前言](quick-start/start-overview.md)
      - [使用eTS语言开发](quick-start/start-with-ets.md)
      - [使用JS语言开发（传统代码方式）](quick-start/start-with-js.md)
      - [使用JS语言开发（低代码方式）](quick-start/start-with-js-low-code.md)
  - [应用开发包结构说明](quick-start/package-structure.md)
  - [资源文件的分类](quick-start/basic-resource-file-categories.md)
- 开发
  - [Ability开发](ability/Readme-CN.md)
    - [Ability框架概述](ability/ability-brief.md)
    - FA模型
      - [FA模型综述](ability/fa-brief.md)
      - [PageAbility开发指导](ability/fa-pageability.md)
      - [ServiceAbility开发指导](ability/fa-serviceability.md)
      - [DataAbility开发指导](ability/fa-dataability.md)
      - [FormAbility开发指导](ability/fa-formability.md)
    - Stage模型
      - [Stage模型综述](ability/stage-brief.md)
      - [Ability开发指导](ability/stage-ability.md)
      - [ServiceExtensionAbility开发指导](ability/stage-serviceextension.md)
      - [FormExtensionAbility开发指导](ability/stage-formextension.md)
      - [应用迁移开发指导](ability/stage-ability-continuation.md)
    - 其他
      - [WantAgent使用指导](ability/wantagent.md)
      - [Ability助手使用指导](ability/ability-assistant-guidelines.md)
  - [UI开发](ui/Readme-CN.md)
    - [方舟开发框架（ArkUI）概述](ui/arkui-overview.md)
    - 基于JS扩展的类Web开发范式
      - [概述](ui/ui-js-overview.md)
      - 框架说明
        - [文件组织](ui/js-framework-file.md)
        - [js标签配置](ui/js-framework-js-tag.md)
        - [app.js](ui/js-framework-js-file.md)
        - 语法
          - [HML语法参考](ui/js-framework-syntax-hml.md)
          - [CSS语法参考](ui/js-framework-syntax-css.md)
          - [JS语法参考](ui/js-framework-syntax-js.md)
        - [生命周期](ui/js-framework-lifecycle.md)
        - [资源限定与访问](ui/js-framework-resource-restriction.md)
        - [多语言支持](ui/js-framework-multiple-languages.md)
      - 构建用户界面
        - [组件介绍](ui/ui-js-building-ui-component.md)
        - 构建布局
          - [布局说明](ui/ui-js-building-ui-layout-intro.md)
          - [添加标题行和文本区域](ui/ui-js-building-ui-layout-text.md)
          - [添加图片区域](ui/ui-js-building-ui-layout-image.md)
          - [添加留言区域](ui/ui-js-building-ui-layout-comment.md)
          - [添加容器](ui/ui-js-building-ui-layout-external-container.md)
        - [添加交互](ui/ui-js-building-ui-interactions.md)
        - [动画](ui/ui-js-building-ui-animation.md)
        - [事件](ui/ui-js-building-ui-event.md)
        - [页面路由](ui/ui-js-building-ui-routes.md)
      - 常见组件开发指导
        - 容器组件
          - [List开发指导](ui/ui-js-components-list.md)
          - [Dialog开发指导](ui/ui-js-components-dialog.md)
          - [Form开发指导](ui/ui-js-components-form.md)
          - [Stepper开发指导](ui/ui-js-components-stepper.md)
          - [Tabs开发指导](ui/ui-js-component-tabs.md)
          - [Swiper开发指导](ui/ui-js-components-swiper.md)
        - 基础组件
          - [Text开发指导](ui/ui-js-components-text.md)
          - [Input开发指导](ui/ui-js-components-input.md)
          - [Button开发指导](ui/ui-js-components-button.md)
          - [Picker开发指导](ui/ui-js-components-picker.md)
          - [Image开发指导](ui/ui-js-components-images.md)
          - [Image-animator开发指导](ui/ui-js-components-image-animator.md)
          - [Rating开发指导](ui/ui-js-components-rating.md)
          - [Slider开发指导](ui/ui-js-components-slider.md)
          - [Chart开发指导](ui/ui-js-components-chart.md)
          - [Switch开发指导](ui/ui-js-components-switch.md)
          - [Toolbar开发指导](ui/ui-js-components-toolbar.md)
          - [Menu开发指导](ui/ui-js-components-menu.md)
          - [Marquee开发指导](ui/ui-js-components-marquee.md)
          - [Qrcode开发指导](ui/ui-js-components-qrcode.md)
          - [Search开发指导](ui/ui-js-components-search.md)
        - Canvas开发指导
          - [CanvasRenderingContext2D对象](ui/ui-js-components-canvasrenderingcontext2d.md)
          - [Path2D对象](ui/ui-js-components-path2d.md)
          - [OffscreenCanvas对象](ui/ui-js-components-offscreencanvas.md)
        - [栅格布局](ui/ui-js-components-calendar.md)
        - Svg开发指导
          - [基础知识](ui/ui-js-components-svg-overview.md)
          - [绘制图形](ui/ui-js-components-svg-graphics.md)
          - [绘制路径](ui/ui-js-components-svg-path.md)
          - [绘制文本](ui/ui-js-components-svg-text.md)
      - 动效开发指导
        - CSS动画
          - [属性样式动画](ui/ui-js-animate-attribute-style.md)
          - [transform样式动画](ui/ui-js-animate-transform.md)
          - [background-position样式动画](ui/ui-js-animate-background-position-style.md)
          - [svg动画](ui/ui-js-animate-svg.md)
        - JS动画
          - [组件动画](ui/ui-js-animate-component.md)
          - 插值器动画
            - [动画动效](ui/ui-js-animate-dynamic-effects.md)
            - [动画帧](ui/ui-js-animate-frame.md)
      - [自定义组件](ui/ui-js-custom-components.md)
    - 基于TS扩展的声明式开发范式
      - [概述](ui/ui-ts-overview.md)
      - 框架说明
        - 文件组织
          - [目录结构](ui/ts-framework-directory.md)
          - [应用代码文件访问规则](ui/ts-framework-file-access-rules.md)
        - [js标签配置](ui/ts-framework-js-tag.md)
        - 资源访问
          - [媒体资源类型说明](ui/ts-media-resource-type.md)
        - [像素单位](ui/ts-pixel-units.md)
        - [类型定义](ui/ts-types.md)
      - 声明式语法
        - [描述规范使用说明](ui/ts-syntax-intro.md)
        - 通用UI描述规范
          - [基本概念](ui/ts-general-ui-concepts.md)
          - 声明式UI描述规范
            - [无构造参数配置](ui/ts-parameterless-configuration.md)
            - [必选参数构造配置](ui/ts-configuration-with-mandatory-parameters.md)
            - [属性配置](ui/ts-attribution-configuration.md)
            - [事件配置](ui/ts-event-configuration.md)
            - [子组件配置](ui/ts-child-component-configuration.md)
          - 组件化
            - [@Component](ui/ts-component-based-component.md)
            - [@Entry](ui/ts-component-based-entry.md)
            - [@Preview](ui/ts-component-based-preview.md)
            - [@Builder](ui/ts-component-based-builder.md)
            - [@Extend](ui/ts-component-based-extend.md)
            - [@CustomDialog](ui/ts-component-based-customdialog.md)
            - [@Styles](ui/ts-component-based-styles.md)
        - UI状态管理
          - [基本概念](ui/ts-ui-state-mgmt-concepts.md)
          - 管理组件拥有的状态
            - [@State](ui/ts-component-states-state.md)
            - [@Prop](ui/ts-component-states-prop.md)
            - [@Link](ui/ts-component-states-link.md)
          - 管理应用程序的状态
            - [应用程序的数据存储](ui/ts-application-states-appstorage.md)
            - [持久化数据管理](ui/ts-application-states-apis-persistentstorage.md)
            - [环境变量](ui/ts-application-states-apis-environment.md)
          - 其他类目的状态管理
            - [Observed和ObjectLink数据管理](ui/ts-other-states-observed-objectlink.md)
            - [@Consume和@Provide数据管理](ui/ts-other-states-consume-provide.md)
            - [@Watch](ui/ts-other-states-watch.md)
        - 渲染控制语法
          - [条件渲染](ui/ts-rending-control-syntax-if-else.md)
          - [循环渲染](ui/ts-rending-control-syntax-foreach.md)
          - [数据懒加载](ui/ts-rending-control-syntax-lazyforeach.md)
        - 深入理解组件化
          - [build函数](ui/ts-function-build.md)
          - [自定义组件初始化](ui/ts-custom-component-initialization.md)
          - [自定义组件生命周期回调函数](ui/ts-custom-component-lifecycle-callbacks.md)
          - [组件创建和重新初始化示例](ui/ts-component-creation-re-initialization.md)
        - [语法糖](ui/ts-syntactic-sugar.md)
      - 体验声明式UI
        - [创建声明式UI工程](ui/ui-ts-creating-project.md)
        - [初识Component](ui/ui-ts-components.md)
        - [创建简单视图](ui/ui-ts-creating-simple-page.md)
      - 页面布局与连接
        - [构建食物数据模型](ui/ui-ts-building-data-model.md)
        - [构建食物列表List布局](ui/ui-ts-building-category-list-layout.md)
        - [构建食物分类Grid布局](ui/ui-ts-building-category-grid-layout.md)
        - [页面跳转与数据传递](ui/ui-ts-page-redirection-data-transmission.md)
  - 基础功能开发
    - 窗口管理
      - 窗口
        - [窗口开发概述](windowmanager/window-overview.md)
        - [窗口开发指导](windowmanager/window-guidelines.md)
      - 显示设备
        - [屏幕属性开发概述](windowmanager/display-overview.md)
        - [屏幕属性开发指导](windowmanager/display-guidelines.md)
      - 屏幕截图
        - [屏幕截图开发概述](windowmanager/screenshot-overview.md)
        - [屏幕截图开发指导](windowmanager/screenshot-guidelines.md)
    - WebGL
      - [概述](webgl/webgl-overview.md)
      - [WebGL开发指导](webgl/webgl-guidelines.md)
    - 媒体
      - 音频
        - [音频开发概述](media/audio-overview.md)
        - [音频播放开发指导](media/audio-playback.md)
        - [音频录制开发指导](media/audio-recorder.md)
        - [音频渲染开发指导](media/audio-renderer.md)
        - [音频采集开发指导](media/audio-capturer.md)
      - 视频
        - [视频播放开发指导](media/video-playback.md)
        - [视频录制开发指导](media/video-recorder.md)
      - 图片
        - [图片开发指导](media/image.md)
    - 安全
      - 用户认证
        - [用户认证开发概述](security/userauth-overview.md)
        - [用户认证开发指导](security/userauth-guidelines.md)
      - 密钥管理
        - [HUKS开发概述](security/huks-overview.md)
        - [HUKS开发指导](security/huks-guidelines.md)
      - Hap包签名工具
        - [Hap包签名工具开发指导](security/hapsigntool-guidelines.md)
      - 访问控制
        - [访问控制开发概述](security/accesstoken-overview.md)
        - [访问控制开发指导](security/accesstoken-guidelines.md)
    - 网络与连接
      - IPC与RPC通信
        - [IPC与RPC通信概述](connectivity/ipc-rpc-overview.md)
        - [IPC与RPC通信开发指导](connectivity/ipc-rpc-development-guideline.md)
        - [远端状态订阅开发实例](connectivity/subscribe-remote-state.md)
    - 数据管理
      - 分布式数据服务
        - [分布式数据服务概述](database/database-mdds-overview.md)
        - [分布式数据服务开发指导](database/database-mdds-guidelines.md)
      - 关系型数据库
        - [关系型数据库概述](database/database-relational-overview.md)
        - [关系型数据库开发指导](database/database-relational-guidelines.md)
      - 轻量级数据存储
        - [轻量级数据存储概述](database/database-preference-overview.md)
        - [轻量级数据存储开发指导](database/database-preference-guidelines.md)
      - 分布式数据对象
        - [分布式数据对象概述](database/database-distributedobject-overview.md)
        - [分布式数据对象开发指导](database/database-distributedobject-guidelines.md)
    - 后台代理提醒
      - [概述](background-agent-scheduled-reminder/background-agent-scheduled-reminder-overview.md)
      - [开发指导](background-agent-scheduled-reminder/background-agent-scheduled-reminder-guide.md)
    - 后台任务管理
      - 后台任务
        - [后台任务概述](background-task-management/background-task-overview.md)
        - [后台任务开发指导](background-task-management/background-task-dev-guide.md)
    - 设备管理
      - USB服务
        - [USB服务开发概述](device/usb-overview.md)
        - [USB服务开发指导](device/usb-guidelines.md)
      - 位置
        - [位置开发概述](device/device-location-overview.md)
        - [获取设备的位置信息](device/device-location-info.md)
        - [（逆）地理编码转化](device/device-location-geocoding.md)
      - 传感器
        - [传感器开发概述](device/sensor-overview.md)
        - [传感器开发指导](device/sensor-guidelines.md)
      - 振动
        - [振动开发概述](device/vibrator-guidelines.md)
        - [振动开发指导](device/vibrator-guidelines.md)
    - 设备使用信息统计
      - [设备使用信息统计概述](device-usage-statistics/device-usage-statistics-overview.md)
      - [设备使用信息统计开发指导](device-usage-statistics/device-usage-statistics-dev-guide.md)
    - DFX
      - 应用事件打点
        - [应用事件打点概述](dfx/hiappevent-overview.md)
        - [应用事件打点开发指导](dfx/hiappevent-guidelines.md)
      - 性能打点跟踪
        - [性能打点跟踪概述](dfx/hitracemeter-overview.md)
        - [性能打点跟踪开发指导](dfx/hitracemeter-guidelines.md)
      - 分布式跟踪
        - [分布式跟踪概述](dfx/hitracechain-overview.md)
        - [分布式跟踪开发指导](dfx/hitracechain-guidelines.md)
    - 国际化
      - [国际化开发概述](internationalization/international-overview.md)
      - [Intl开发指导](internationalization/intl-guidelines.md)
      - [I18n开发指导](internationalization/i18n-guidelines.md)
- 工具
  - DevEco Studio（OpenHarmony）使用指南
    - [概述](quick-start/deveco-studio-overview.md)
    - [版本变更说明](quick-start/deveco-studio-release-notes.md)
    - [配置OpenHarmony SDK](quick-start/configuring-openharmony-sdk.md)
    - [创建OpenHarmony工程](quick-start/create-openharmony-project.md)
    - [配置OpenHarmony应用签名信息](quick-start/configuring-openharmony-app-signature.md)
    - [安装运行OpenHarmony应用](quick-start/installing-openharmony-app.md)
- 示例教程
  - [示例代码](https://gitee.com/openharmony/app_samples/blob/master/README_zh.md)
  - [Codelabs](https://gitee.com/openharmony/codelabs/blob/master/README.md)
- API参考
  - 组件参考（基于JS扩展的类Web开发范式）
    - 组件
      - 通用
        - [通用属性](reference/arkui-js/js-components-common-attributes.md)
        - [通用样式](reference/arkui-js/js-components-common-styles.md)
        - [通用事件](reference/arkui-js/js-components-common-events.md)
        - [通用方法](reference/arkui-js/js-components-common-methods.md)
        - [动画样式](reference/arkui-js/js-components-common-animation.md)
        - [渐变样式](reference/arkui-js/js-components-common-gradient.md)
        - [转场样式](reference/arkui-js/js-components-common-transition.md)
        - [自定义字体样式](reference/arkui-js/js-components-common-customizing-font.md)
        - [原子布局](reference/arkui-js/js-components-common-atomic-layout.md)
      - 容器组件
        - [badge](reference/arkui-js/js-components-container-badge.md)
        - [dialog](reference/arkui-js/js-components-container-dialog.md)
        - [div](reference/arkui-js/js-components-container-div.md)
        - [form](reference/arkui-js/js-components-container-form.md)
        - [list](reference/arkui-js/js-components-container-list.md)
        - [list-item](reference/arkui-js/js-components-container-list-item.md)
        - [list-item-group](reference/arkui-js/js-components-container-list-item-group.md)
        - [panel](reference/arkui-js/js-components-container-panel.md)
        - [popup](reference/arkui-js/js-components-container-popup.md)
        - [refresh](reference/arkui-js/js-components-container-refresh.md)
        - [stack](reference/arkui-js/js-components-container-stack.md)
        - [stepper](reference/arkui-js/js-components-container-stepper.md)
        - [stepper-item](reference/arkui-js/js-components-container-stepper-item.md)
        - [swiper](reference/arkui-js/js-components-container-swiper.md)
        - [tabs](reference/arkui-js/js-components-container-tabs.md)
        - [tab-bar](reference/arkui-js/js-components-container-tab-bar.md)
        - [tab-content](reference/arkui-js/js-components-container-tab-content.md)
      - 基础组件
        - [button](reference/arkui-js/js-components-basic-button.md)
        - [chart](reference/arkui-js/js-components-basic-chart.md)
        - [divider](reference/arkui-js/js-components-basic-divider.md)
        - [image](reference/arkui-js/js-components-basic-image.md)
        - [image-animator](reference/arkui-js/js-components-basic-image-animator.md)
        - [input](reference/arkui-js/js-components-basic-input.md)
        - [label](reference/arkui-js/js-components-basic-label.md)
        - [marquee](reference/arkui-js/js-components-basic-marquee.md)
        - [menu](reference/arkui-js/js-components-basic-menu.md)
        - [option](reference/arkui-js/js-components-basic-option.md)
        - [picker](reference/arkui-js/js-components-basic-picker.md)
        - [picker-view](reference/arkui-js/js-components-basic-picker-view.md)
        - [piece](reference/arkui-js/js-components-basic-piece.md)
        - [progress](reference/arkui-js/js-components-basic-progress.md)
        - [qrcode](reference/arkui-js/js-components-basic-qrcode.md)
        - [rating](reference/arkui-js/js-components-basic-rating.md)
        - [richtext](reference/arkui-js/js-components-basic-richtext.md)
        - [search](reference/arkui-js/js-components-basic-search.md)
        - [select](reference/arkui-js/js-components-basic-select.md)
        - [slider](reference/arkui-js/js-components-basic-slider.md)
        - [span](reference/arkui-js/js-components-basic-span.md)
        - [switch](reference/arkui-js/js-components-basic-switch.md)
        - [text](reference/arkui-js/js-components-basic-text.md)
        - [textarea](reference/arkui-js/js-components-basic-textarea.md)
        - [toolbar](reference/arkui-js/js-components-basic-toolbar.md)
        - [toolbar-item](reference/arkui-js/js-components-basic-toolbar-item.md)
        - [toggle](reference/arkui-js/js-components-basic-toggle.md)
        - [web](reference/arkui-js/js-components-basic-web.md)
      - 媒体组件
        - [video](reference/arkui-js/js-components-media-video.md)
      - 画布组件
        - [canvas组件](reference/arkui-js/js-components-canvas-canvas.md)
        - [CanvasRenderingContext2D对象](reference/arkui-js/js-components-canvas-canvasrenderingcontext2d.md)
        - [Image对象](reference/arkui-js/js-components-canvas-image.md)
        - [CanvasGradient对象](reference/arkui-js/js-components-canvas-canvasgradient.md)
        - [ImageData对象](reference/arkui-js/js-components-canvas-imagedata.md)
        - [Path2D对象](reference/arkui-js/js-components-canvas-path2d.md)
        - [ImageBitmap对象](reference/arkui-js/js-components-canvas-imagebitmap.md)
        - [OffscreenCanvas对象](reference/arkui-js/js-components-canvas-offscreencanvas.md)
        - [OffscreenCanvasRenderingContext2D对象](reference/arkui-js/js-offscreencanvasrenderingcontext2d.md)
      - 栅格组件
        - [基本概念](reference/arkui-js/js-components-grid-basic-concepts.md)
        - [grid-container](reference/arkui-js/js-components-grid-container.md)
        - [grid-row](reference/arkui-js/js-components-grid-row.md)
        - [grid-col](reference/arkui-js/js-components-grid-col.md)
      - svg组件
        - [通用属性](reference/arkui-js/js-components-svg-common-attributes.md)
        - [svg](reference/arkui-js/js-components-svg.md)
        - [rect](reference/arkui-js/js-components-svg-rect.md)
        - [circle](reference/arkui-js/js-components-svg-circle.md)
        - [ellipse](reference/arkui-js/js-components-svg-ellipse.md)
        - [path](reference/arkui-js/js-components-svg-path.md)
        - [line](reference/arkui-js/js-components-svg-line.md)
        - [polyline](reference/arkui-js/js-components-svg-polyline.md)
        - [polygon](reference/arkui-js/js-components-svg-polygon.md)
        - [text](reference/arkui-js/js-components-svg-text.md)
        - [tspan](reference/arkui-js/js-components-svg-tspan.md)
        - [textPath](reference/arkui-js/js-components-svg-textpath.md)
        - [animate](reference/arkui-js/js-components-svg-animate.md)
        - [animateMotion](reference/arkui-js/js-components-svg-animatemotion.md)
        - [animateTransform](reference/arkui-js/js-components-svg-animatetransform.md)
    - 自定义组件
      - [基本用法](reference/arkui-js/js-components-custom-basic-usage.md)
      - [自定义事件](reference/arkui-js/js-components-custom-events.md)
      - [Props](reference/arkui-js/js-components-custom-props.md)
      - [事件参数](reference/arkui-js/js-components-custom-event-parameter.md)
      - [slot插槽](reference/arkui-js/js-components-custom-slot.md)
      - [生命周期定义](reference/arkui-js/js-components-custom-lifecycle.md)
    - 附录
      - [类型说明](reference/arkui-js/js-appendix-types.md)
  - 组件参考（基于TS扩展的声明式开发范式）
    - 组件
      - 通用
        - 通用事件
          - [点击事件](reference/arkui-ts/ts-universal-events-click.md)
          - [触摸事件](reference/arkui-ts/ts-universal-events-touch.md)
          - [挂载卸载事件](reference/arkui-ts/ts-universal-events-show-hide.md)
          - [拖拽事件](reference/arkui-ts/ts-universal-events-drag-drop.md)
          - [按键事件](reference/arkui-ts/ts-universal-events-key.md)
          - [焦点事件](reference/arkui-ts/ts-universal-focus-event.md)
          - [鼠标事件](reference/arkui-ts/ts-universal-mouse-key.md)
          - [组件区域变化事件](reference/arkui-ts/ts-universal-component-area-change-event.md)
        - 通用属性
          - [尺寸设置](reference/arkui-ts/ts-universal-attributes-size.md)
          - [位置设置](reference/arkui-ts/ts-universal-attributes-location.md)
          - [布局约束](reference/arkui-ts/ts-universal-attributes-layout-constraints.md)
          - [Flex布局](reference/arkui-ts/ts-universal-attributes-flex-layout.md)
          - [边框设置](reference/arkui-ts/ts-universal-attributes-border.md)
          - [背景设置](reference/arkui-ts/ts-universal-attributes-background.md)
          - [透明度设置](reference/arkui-ts/ts-universal-attributes-opacity.md)
          - [显隐控制](reference/arkui-ts/ts-universal-attributes-visibility.md)
          - [禁用控制](reference/arkui-ts/ts-universal-attributes-enable.md)
          - [浮层](reference/arkui-ts/ts-universal-attributes-overlay.md)
          - [Z序控制](reference/arkui-ts/ts-universal-attributes-z-order.md)
          - [图形变换](reference/arkui-ts/ts-universal-attributes-transformation.md)
          - [图像效果](reference/arkui-ts/ts-universal-attributes-image-effect.md)
          - [形状裁剪](reference/arkui-ts/ts-universal-attributes-sharp-clipping.md)
          - [文本样式设置](reference/arkui-ts/ts-universal-attributes-text-style.md)
          - [栅格设置](reference/arkui-ts/ts-universal-attributes-grid.md)
          - [颜色渐变](reference/arkui-ts/ts-universal-attributes-gradient-color.md)
          - [Popup控制](reference/arkui-ts/ts-universal-attributes-popup.md)
          - [Menu控制](reference/arkui-ts/ts-universal-attributes-menu.md)
          - [点击控制](reference/arkui-ts/ts-universal-attributes-click.md)
          - [焦点控制](reference/arkui-ts/ts-universal-attributes-focus.md)
          - [悬浮态效果](reference/arkui-ts/ts-universal-attributes-hover-effect.md)
          - [组件标识](reference/arkui-ts/ts-universal-attributes-component-id.md)
          - [触摸热区设置](reference/arkui-ts/ts-universal-attributes-touch-target.md)
          - [多态样式](reference/arkui-ts/ts-universal-attributes-polymorphic-style.md)
        - 手势处理
          - [绑定手势方法](reference/arkui-ts/ts-gesture-settings.md)
          - 基础手势
            - [TapGesture](reference/arkui-ts/ts-basic-gestures-tapgesture.md)
            - [LongPressGesture](reference/arkui-ts/ts-basic-gestures-longpressgesture.md)
            - [PanGesture](reference/arkui-ts/ts-basic-gestures-pangesture.md)
            - [PinchGesture](reference/arkui-ts/ts-basic-gestures-pinchgesture.md)
            - [RotationGesture](reference/arkui-ts/ts-basic-gestures-rotationgesture.md)
            - [SwipeGesture](reference/arkui-ts/ts-basic-gestures-swipegesture.md)
          - [组合手势](reference/arkui-ts/ts-combined-gestures.md)
      - 基础组件
        - [Blank](reference/arkui-ts/ts-basic-components-blank.md)
        - [Button](reference/arkui-ts/ts-basic-components-button.md)
        - [Checkbox](reference/arkui-ts/ts-basic-components-checkbox.md)
        - [CheckboxGroup](reference/arkui-ts/ts-basic-components-checkboxgroup.md)
        - [DataPanel](reference/arkui-ts/ts-basic-components-datapanel.md)
        - [DatePicker](reference/arkui-ts/ts-basic-components-datepicker.md)
        - [Divider](reference/arkui-ts/ts-basic-components-divider.md)
        - [Image](reference/arkui-ts/ts-basic-components-image.md)
        - [ImageAnimator](reference/arkui-ts/ts-basic-components-imageanimator.md)
        - [LoadingProgress](reference/arkui-ts/ts-basic-components-loadingprogress.md)
        - [Progress](reference/arkui-ts/ts-basic-components-progress.md)
        - [QRCode](reference/arkui-ts/ts-basic-components-qrcode.md)
        - [Radio](reference/arkui-ts/ts-basic-components-radio.md)
        - [Rating](reference/arkui-ts/ts-basic-components-rating.md)
        - [Select](reference/arkui-ts/ts-basic-components-select.md)
        - [Slider](reference/arkui-ts/ts-basic-components-slider.md)
        - [Span](reference/arkui-ts/ts-basic-components-span.md)
        - [Text](reference/arkui-ts/ts-basic-components-text.md)
        - [TextArea](reference/arkui-ts/ts-basic-components-textarea.md)
        - [TextInput](reference/arkui-ts/ts-basic-components-textinput.md)
        - [TextPicker](reference/arkui-ts/ts-basic-components-textpicker.md)
        - [TextTimer](reference/arkui-ts/ts-basic-components-texttimer.md)
        - [Toggle](reference/arkui-ts/ts-basic-components-toggle.md)
        - [TextClock](reference/arkui-ts/ts-basic-components-textclock.md)
        - [Web](reference/arkui-ts/ts-basic-components-web.md)
      - 容器组件
        - [AlphabetIndexer](reference/arkui-ts/ts-container-alphabet-indexer.md)
        - [Badge](reference/arkui-ts/ts-container-badge.md)
        - [Column](reference/arkui-ts/ts-container-column.md)
        - [ColumnSplit](reference/arkui-ts/ts-container-columnsplit.md)
        - [Counter](reference/arkui-ts/ts-container-counter.md)
        - [Flex](reference/arkui-ts/ts-container-flex.md)
        - [GridContainer](reference/arkui-ts/ts-container-gridcontainer.md)
        - [Grid](reference/arkui-ts/ts-container-grid.md)
        - [GridItem](reference/arkui-ts/ts-container-griditem.md)
        - [List](reference/arkui-ts/ts-container-list.md)
        - [ListItem](reference/arkui-ts/ts-container-listitem.md)
        - [Navigator](reference/arkui-ts/ts-container-navigator.md)
        - [Navigation](reference/arkui-ts/ts-basic-components-navigation.md)
        - [Panel](reference/arkui-ts/ts-container-panel.md)
        - [Row](reference/arkui-ts/ts-container-row.md)
        - [RowSplit](reference/arkui-ts/ts-container-rowsplit.md)
        - [Scroll](reference/arkui-ts/ts-container-scroll.md)
        - [ScrollBar](reference/arkui-ts/ts-basic-components-scrollbar.md)
        - [SideBarContainer](reference/arkui-ts/ts-container-sidebarcontainer.md)
        - [Stack](reference/arkui-ts/ts-container-stack.md)
        - [Swiper](reference/arkui-ts/ts-container-swiper.md)
        - [Tabs](reference/arkui-ts/ts-container-tabs.md)
        - [TabContent](reference/arkui-ts/ts-container-tabcontent.md)
        - [Refresh](reference/arkui-ts/ts-container-refresh.md)
      - 媒体组件
        - [Video](reference/arkui-ts/ts-media-components-video.md)
      - 绘制组件
        - [Circle](reference/arkui-ts/ts-drawing-components-circle.md)
        - [Ellipse](reference/arkui-ts/ts-drawing-components-ellipse.md)
        - [Line](reference/arkui-ts/ts-drawing-components-line.md)
        - [Polyline](reference/arkui-ts/ts-drawing-components-polyline.md)
        - [Polygon](reference/arkui-ts/ts-drawing-components-polygon.md)
        - [Path](reference/arkui-ts/ts-drawing-components-path.md)
        - [Rect](reference/arkui-ts/ts-drawing-components-rect.md)
        - [Shape](reference/arkui-ts/ts-drawing-components-shape.md)
      - 画布组件
        - [Canvas](reference/arkui-ts/ts-components-canvas-canvas.md)
        - [CanvasRenderingContext2D对象](reference/arkui-ts/ts-canvasrenderingcontext2d.md)
        - [OffscreenCanvasRenderingConxt2D对象](reference/arkui-ts/ts-offscreencanvasrenderingcontext2d.md)
        - [Lottie](reference/arkui-ts/ts-components-canvas-lottie.md)
        - [Path2D对象](reference/arkui-ts/ts-components-canvas-path2d.md)
        - [CanvasGradient对象](reference/arkui-ts/ts-components-canvas-canvasgradient.md)
        - [ImageBitmap对象](reference/arkui-ts/ts-components-canvas-imagebitmap.md)
        - [ImageData对象](reference/arkui-ts/ts-components-canvas-imagedata.md)
    - 动画
      - [属性动画](reference/arkui-ts/ts-animatorproperty.md)
      - [显式动画](reference/arkui-ts/ts-explicit-animation.md)
      - 转场动画
        - [页面间转场](reference/arkui-ts/ts-page-transition-animation.md)
        - [组件内转场](reference/arkui-ts/ts-transition-animation-component.md)
        - [共享元素转场](reference/arkui-ts/ts-transition-animation-shared-elements.md)
      - [路径动画](reference/arkui-ts/ts-motion-path-animation.md)
      - [矩阵变换](reference/arkui-ts/ts-matrix-transformation.md)
      - [插值计算](reference/arkui-ts/ts-interpolation-calculation.md)
    - 全局UI方法
      - [图片缓存](reference/arkui-ts/ts-methods-image-cache.md)
      - [媒体查询](reference/arkui-ts/ts-methods-media-query.md)
      - 弹窗
        - [警告弹窗](reference/arkui-ts/ts-methods-alert-dialog-box.md)
        - [列表选择弹窗](reference/arkui-ts/ts-methods-action-sheet.md)
        - [自定义弹窗](reference/arkui-ts/ts-methods-custom-dialog-box.md)
        - [日期时间选择弹窗](reference/arkui-ts/ts-methods-datepicker-dialog.md)
        - [文本选择弹窗](reference/arkui-ts/ts-methods-textpicker-dialog.md)
      - [菜单](reference/arkui-ts/ts-methods-menu.md)
    - 附录
      - [文档中涉及到的内置枚举值](reference/arkui-ts/ts-appendix-enums.md)
  - 接口参考
    - Ability框架
      - [FeatureAbility模块](reference/apis/js-apis-featureAbility.md)
      - [ParticleAbility模块](reference/apis/js-apis-particleAbility.md)
      - [DataAbilityHelper模块](reference/apis/js-apis-dataAbilityHelper.md)
      - [DataUriUtils模块](reference/apis/js-apis-DataUriUtils.md)
      - [Bundle模块](reference/apis/js-apis-Bundle.md)
      - [Context模块](reference/apis/js-apis-Context.md)
    - 事件与通知
      - [CommonEvent模块](reference/apis/js-apis-commonEvent.md)
      - [Notification模块](reference/apis/js-apis-notification.md)
      - [后台代理提醒](reference/apis/js-apis-reminderAgent.md)
    - 资源管理
      - [资源管理](reference/apis/js-apis-resource-manager.md)
      - [国际化-Intl](reference/apis/js-apis-intl.md)
      - [国际化-I18n](reference/apis/js-apis-i18n.md)
    - 媒体
      - [音频管理](reference/apis/js-apis-audio.md)
      - [媒体服务](reference/apis/js-apis-media.md)
      - [图片处理](reference/apis/js-apis-image.md)
      - [相机管理](reference/apis/js-apis-camera.md)
    - 安全
      - [用户认证](reference/apis/js-apis-useriam-userauth.md)
      - [访问控制](reference/apis/js-apis-abilityAccessCtrl.md)
      - [通用密钥库系统](reference/apis/js-apis-huks.md)
    - 数据管理
      - [轻量级存储](reference/apis/js-apis-data-preferences.md)
      - [分布式数据管理](reference/apis/js-apis-distributed-data.md)
      - [关系型数据库](reference/apis/js-apis-data-rdb.md)
      - [结果集](reference/apis/js-apis-data-resultset.md)
      - [DataAbility 谓词](reference/apis/js-apis-data-ability.md)
      - [设置数据项名称](reference/apis/js-apis-settings.md)
    - 文件管理
      - [文件管理](reference/apis/js-apis-fileio.md)
      - [Statfs](reference/apis/js-apis-statfs.md)
      - [目录环境](reference/apis/js-apis-environment.md)
      - [公共文件访问与管理](reference/apis/js-apis-filemanager.md)
      - [应用空间统计](reference/apis/js-apis-storage-statistics.md)
      - [卷管理](reference/apis/js-apis-volumemanager.md)
    - 账号管理
      - [系统帐号管理](reference/apis/js-apis-osAccount.md)
      - [分布式帐号管理](reference/apis/js-apis-distributed-account.md)
      - [应用帐号管理](reference/apis/js-apis-appAccount.md)
    - 电话服务
      - [拨打电话](reference/apis/js-apis-call.md)
      - [短信服务](reference/apis/js-apis-sms.md)
      - [SIM卡管理](reference/apis/js-apis-sim.md)
      - [网络搜索](reference/apis/js-apis-radio.md)
      - [observer](reference/apis/js-apis-observer.md)
      - [蜂窝数据](reference/apis/js-apis-telephony-data.md)
    - 网络管理
      - [网络连接管理](reference/apis/js-apis-net-connection.md)
      - [Socket连接](reference/apis/js-apis-socket.md)
      - [WebSocket连接](reference/apis/js-apis-webSocket.md)
      - [数据请求](reference/apis/js-apis-http.md)
    - 通信与连接
      - [WLAN](reference/apis/js-apis-wifi.md)
      - [Bluetooth](reference/apis/js-apis-bluetooth.md)
      - [RPC通信](reference/apis/js-apis-rpc.md)
    - 设备管理
      - [传感器](reference/apis/js-apis-sensor.md)
      - [振动](reference/apis/js-apis-vibrator.md)
      - [屏幕亮度](reference/apis/js-apis-brightness.md)
      - [电量信息](reference/apis/js-apis-battery-info.md)
      - [系统电源管理](reference/apis/js-apis-power.md)
      - [热管理](reference/apis/js-apis-thermal.md)
      - [Runninglock锁](reference/apis/js-apis-runninglock.md)
      - [设备信息](reference/apis/js-apis-device-info.md)
      - [系统属性](reference/apis/js-apis-system-parameter.md)
      - [设备管理](reference/apis/js-apis-device-manager.md)
      - [窗口](reference/apis/js-apis-window.md)
      - [显示设备属性](reference/apis/js-apis-display.md)
      - [升级](reference/apis/js-apis-update.md)
      - [USB管理](reference/apis/js-apis-usb.md)
      - [位置服务](reference/apis/js-apis-geolocation.md)
    - 基本功能
      - [应用上下文](reference/apis/js-apis-system-app.md)
      - [日志打印](reference/apis/js-apis-basic-features-logs.md)
      - [页面路由](reference/apis/js-apis-system-router.md)
      - [弹窗](reference/apis/js-apis-system-prompt.md)
      - [应用配置](reference/apis/js-apis-system-configuration.md)
      - [定时器](reference/apis/js-apis-basic-features-timer.md)
      - [设置系统时间](reference/apis/js-apis-system-time.md)
      - [动画](reference/apis/js-apis-basic-features-animator.md)
      - [WebGL](reference/apis/js-apis-webgl.md)
      - [WebGL2](reference/apis/js-apis-webgl2.md)
      - [屏幕截图](reference/apis/js-apis-screenshot.md)
      - [输入法框架](reference/apis/js-apis-inputmethod.md)
      - [输入法服务](reference/apis/js-apis-inputmethodengine.md)
      - [辅助功能](reference/apis/js-apis-accessibility.md)
    - DFX
      - [应用打点](reference/apis/js-apis-hiappevent.md)
      - [性能打点](reference/apis/js-apis-hitracemeter.md)
      - [故障日志获取](reference/apis/js-apis-faultLogger.md)
      - [分布式跟踪](reference/apis/js-apis-hitracechain.md)
      - [日志打印](reference/apis/js-apis-hilog.md)
      - [检测模式](reference/apis/js-apis-hichecker.md)
      - [Debug调试](reference/apis/js-apis-hidebug.md)
    - 语言基础类库
      - [获取进程相关的信息](reference/apis/js-apis-process.md)
      - [URL字符串解析](reference/apis/js-apis-url.md)
      - [URI字符串解析](reference/apis/js-apis-uri.md)
      - [util工具函数](reference/apis/js-apis-util.md)
      - [xml解析与生成](reference/apis/js-apis-xml.md)
      - [xml转换JavaScript](reference/apis/js-apis-convertxml.md)
      - [启动一个worker](reference/apis/js-apis-worker.md)
      - [线性容器ArrayList](reference/apis/js-apis-arraylist.md)
      - [线性容器Deque](reference/apis/js-apis-deque.md)
      - [线性容器List](reference/apis/js-apis-list.md)
      - [线性容器LinkedList](reference/apis/js-apis-linkedlist.md)
      - [线性容器Queue](reference/apis/js-apis-queue.md)
      - [线性容器Stack](reference/apis/js-apis-stack.md)
      - [线性容器Vector](reference/apis/js-apis-vector.md)
      - [非线性容器HashSet](reference/apis/js-apis-hashset.md)
      - [非线性容器HashMap](reference/apis/js-apis-hashmap.md)
      - [非线性容器PlainArray](reference/apis/js-apis-plainarray.md)
      - [非线性容器TreeMap](reference/apis/js-apis-treemap.md)
      - [非线性容器TreeSet](reference/apis/js-apis-treeset.md)
      - [非线性容器LightWeightMap](reference/apis/js-apis-lightweightmap.md)
      - [非线性容器LightWeightSet](reference/apis/js-apis-lightweightset.md)
    - 定制管理
      - [配置策略](reference/apis/js-apis-config-policy.md)
      - [企业设备管理](reference/apis/js-apis-enterprise-device-manager.md)