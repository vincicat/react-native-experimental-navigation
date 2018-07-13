# react-native-experimental-navigation
This repo is the fork from reactXP ExperimentalNavigation, hopefully they will not update again.
RN compatibility > 0.44

## Usage
RN > 0.44:
```
import NavigationExperimental from 'react-native-experimental-navigation'
const {
  StateUtils: NavigationStateUtils,
  Transitioner: NavigationTransitioner,
  Card: NavigationCard,
  CardStack: NavigationCardStack,
  Header: NavigationHeader,
} = NavigationExperimental
```
*** For RN 0.39 ~ RN 0.43, Use `import { NavigationExperimental } from 'react-native'` instead.

## Release Note from Microsoft Open Source
ExperimentalNavigation is a cross-platform app navigation framework.
The code in this repository is based on react-native-experimental-navigation deprecated by facebook. See: https://github.com/facebook/react-native/commit/08dbc43fa64ff1dfc0d364b6cef6262426f76b64
*Be aware of facebook patent notice if you are using it.*

### Why ExperimentalNavigation
If you need in good low-level navigation framework this library is a good answer. It has a better performance than StandardNavigation framework, though not all of the StandardNavigation features are implemented in particular some of the animations behave differently.

If you are building something new you'd probably better to look at the https://reactnavigation.org/.

### Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

You must sign a Contribution License Agreement (CLA) before your PR will be merged. This a one-time requirement for Microsoft projects in GitHub. You can read more about [Contribution License Agreements (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement) on Wikipedia. You can sign the Microsoft Contribution License Agreement by visiting https://cla.microsoft.com/. Use your GitHub account to login.

#### License
This project is licensed under the BSD-3-Clause License - see the [LICENSE](LICENSE) file for details

