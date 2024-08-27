# Change Log

## [4.0.3] 2024-08-19

- Update dependencies
- Fix DefaultProps deprecation warnings

## [4.0.2] 2023-08-23

- Fix react hooks rule issue

## [4.0.1] 2023-05-29

- Update dependencies
- Fix installation issues

## [4.0.0] 2022-07-04

- Rename components prefix from Sui to Soft.
- Update dependencies.
- Fix the peer dependencies issue.
- Fix the eslint issue with react-app.
- Migrate eslint config from airbnb to react-app.

## [3.1.0] 2022-03-02

### Bug fixing

- Add the color prop to the useMemo dependencies list of ProgressLineChart
- Fix the non-nested route issue
- Momoized the context provider values
- Fix the conditionally used of useContext for SoftPagination component
- Fix the import/no-anonymouse-default-export
- Add a new command `install:peer-deps` for fixing the peer dependencies issue when installing the dependencies using npm

### Major style changes

### Deleted components

### Added components

### Deleted dependencies

```
react-html-parser
react-tilt
```

### Added dependencies

```
html-react-parser
vanilla-tilt
```

### Updated dependencies

```
@asseinfo/react-kanban               2.1.0          →         2.2.0
@emotion/cache                       11.4.0         →         11.7.1
@emotion/react                       11.4.1         →         11.8.1
@emotion/styled                      11.3.0         →         11.8.1
@fullcalendar/daygrid                5.9.0          →         5.10.1
@fullcalendar/interaction            5.9.0          →         5.10.1
@fullcalendar/react                  5.9.0          →         5.10.1
@fullcalendar/timegrid               5.9.0          →         5.10.1
@mui/icons-material                  5.1.1          →         5.4.2
@mui/material                        5.1.1          →         5.4.3
@mui/styled-engine                   5.1.1          →         5.4.2
@react-leaflet/core                  1.0.2          →         1.1.1
@testing-library/jest-dom            5.11.4         →         5.16.2
@testing-library/react               11.1.0         →         12.1.3
@testing-library/user-event          12.1.10        →         13.5.0
chroma-js                            2.1.2          →         2.4.2
dropzone                             5.9.2          →         5.9.3
prop-types                           15.7.2         →         15.8.1
react-countup                        5.2.0          →         6.1.1
react-images-viewer                  1.6.7          →         1.7.1
react-leaflet                        2.7.0          →         3.2.5
react-router-dom                     5.2.0          →         6.2.1
react-scripts                        4.0.3          →         5.0.0
react-select                         4.3.1          →         5.2.2
stylis                               4.0.10         →         4.0.13
stylis-plugin-rtl                    2.1.0          →         2.1.1
sweetalert2                          11.1.2         →         11.4.4
web-vitals                           1.0.1          →         2.1.4
yup                                  0.32.9         →         0.32.11
```

### Warning

There are 2 warnings related to the stylis-plugin-rtl and @pathofdev/react-tag-input dependencies that won't affect on the behavior of the product its something with these libraries itself.

## [3.0.0] 2021-11-23

### Bug fixing

### Major style changes

- Migration from JSS to MUI `styled` api, emotion and `sx` prop.
- The `box-shadow`, `border-radius` and `typography` `regular` size renamed to `md` for theme
- The `backgroundColor` prop renamed to `bgColor` for components
- The `boxShadow` prop renamed to `shadow` for components
- SoftBox `backgroundGradient` prop replaced with `variant: ["contained", "gradient"]`
- SoftButton `buttonColor` prop renamed to `color`
- SoftSocialButton `buttonColor` prop renamed to `color`
- SoftBadge `size` prop updated to ["xs", "sm", "md", "lg"]
- SoftBadgeDot `size` prop updated to ["xs", "sm", "md", "lg"]
- SoftBadgeDot `gradient` prop replaced with `variant: ["contained", "gradient"]`
- SoftInput `withIcon` prop renamed to `icon`
- SoftProgress `gradient` prop replaced with `variant: ["contained", "gradient"]`
- SoftTypography `textColor` prop renamed to `color`
- SoftSnackbar `type` prop renamed to `color`
- New prop `bgWhite` added for SoftSnackbar
- WheatherCard renamed to WeatherCard
- WheatherCard `wheather` prop renamed to `weather`
- PageRoutes renamed to page.routes.js
- Sidenav is more dynamic now, color, brand, brandName props are added

### Deleted components

### Added components

- src/examples/Cards/BlogCards/SimpleBlogCard
- src/examples/Cards/BlogCards/WavedBlogCard
- src/examples/Cards/TeamCards/DefaultTeamCard
- src/examples/Cards/TeamCards/ComplexTeamCard
- src/examples/Cards/PricingCards/OutlinedPricingCard
- src/examples/Cards/PricingCards/WavedPricingCard
- src/examples/Cards/ProfileCards/SimpleProfileCard
- src/examples/Cards/ProfileCards/DefaultProfileCard
- src/examples/Cards/ProfileCards/ComplexProfileCard
- src/examples/Cards/BackgroundCards/DefaultBackgroundCard
- src/examples/Cards/BackgroundCards/SimpleBackgroundCard

### Deleted dependencies

```
- jss
- jss-rtl
- @mui/styles
```

### Added dependencies

```
@three-ts/orbit-controls
```

### Updated dependencies

```
@mui/icons-material                5.0.0-rc.1       →     5.1.1
@mui/material                      5.0.0-rc.1       →     5.1.1
@mui/styled-engine                 5.0.0-rc.1       →     5.1.1
react-quill                        2.0.0-beta.2     →     1.3.5
```

### Warning

## [2.0.0] 2021-09-20

### Bug fixing

### Major style changes

- Migration from Material-UI v4 to Material-UI v5.
- Customizing Autocomplete component based on the Soft Design.
- Customizing the TextField component based on the Soft Design.

### Deleted components

### Added components

### Deleted dependencies

```
- @material-ui/core
- @material-ui/icons
- @material-ui/styles
```

### Added dependencies

```
- @emotion/cache
- @emotion/react
- @emotion/react
- @emotion/styled
- @mui/icons-material
- @mui/material
- @mui/styled-engine
- @mui/styles
- stylis
- stylis-plugin-rtl
```

### Updated dependencies

### Warning

The soft-ui-dashboard-pro-react/pages/rtl is chaning the route slowly in development mode its a problem with @emotion/cache `prepend` and we will fix it on our future updates.

## [1.0.0] 2021-09-02

### Original Release
