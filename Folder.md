.
└── src/
├── assets/
│ ├── fonts
│ └── images
├── components/
│ ├── atoms `#Smallest possible component`
│ ├── molecules `#Composit of one or more component of atoms`
│ ├── organisms `#Combination of molecules`
│ ├── templates `#Collection of organism`
│ └── pages `#A complete page`
├── container `#Can pull al screen based component i.e. SplashScreen, Homescreen, sidebar, tabs`
├── i18n `#Hold Translation`
├── navigation `#Project navigation`
├── screens `#If you have multiple Screens like auth, register, profile, setting`
├── store/
│ ├── actions
│ ├── reducer
│ ├── sagas
│ └── services
├── utils `#utils/helpers files go here that storing reusable methods and logic`
├── hooks `#Any custom hooks`
├── theme `#Global font, styles, colors, metrices`
├── constant.js `#Contains static value`
├── reducer.js `#`
└── service.js `#contains logic, related to external API communications`
