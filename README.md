# ant-design-vue less compile issue

I am attempting to create a way to dynamically switch between light and dark themes. The best way I could figure to do this involved:

1. Utilize ConfigProvider and prefixCls to prefix ant-light or ant-dark depending on the selected theme
2. Create custom light-theme.less and dark-theme.less files that can be compiled into two stylesheets utilizing @ant-prefix to change prefixes to match prefixCls.

However when following the Customize Theme instructions the generated css still uses the prefix ant and not the custom prefixes.
