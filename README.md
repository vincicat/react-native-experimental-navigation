# react-native-experimental-navigation
React Native ExperimentalNavigation clone

## This package is obsolete and no longer supported
Please use v4 version  (based on ReactNavigation.org) of react-native-router-flux instead

## State changes (from 0.26 to 0.43)
- scene.navigationState:NavigationRoute => scene.route:NavigationRoute: \"The data type of  `scene.navigationState` is `NavigationRoute`. Rename  `scene.navigationState` to
`scene.route` to avoid confusion such as treating `scene.navigationState` as the actual global navigation
state (type: NavigationState).\"[807726b](https://github.com/facebook/react-native/commit/807726bcb47ef5b17860c5969a661bee1f8fc651#diff-e969211c2016f40df972f54471383056)
- Rename `navigationState.children` to `navigationState.routes`[1e62602](https://github.com/facebook/react-native/commit/1e626027f58093297ee3b5b73baa9a645ff6a36e#diff-e969211c2016f40df972f54471383056)
- Remove `key` from `NavigationState`. [f7279b4](https://github.com/facebook/react-native/commit/f7279b407471bcc15ffe730e1049c4f7c6f0d108#diff-e969211c2016f40df972f54471383056)
