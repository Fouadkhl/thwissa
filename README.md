# tourisme_app
thwissa app is for local and foreign visitors want to discover Algeria, also for tourist agencies.
## Features
- Tourist Guide (Regions, States, Places)
- Recommendation of tourist places
- Overview of Articles, Photos, Reviews, Nearby Services, Location in gps
- Stories (sharing photos )
- NEWS (travel, advertising and agency promotions)
- Post trips like an agency
- Discussions & Answers
## architecture 
This project follows the famous MVVM architecture 
![mvvm archi photo](https://user-images.githubusercontent.com/87452175/161861860-2b8d2829-89f6-49d9-83e1-5e46d4d34c45.png)
## tech stack
- kotlin and java as programming languages
- Retrofit for data request and response 
- Moshi for parsing JSON
- tbuonomo for dots indicators

## project structure

```
├── App.kt
├── data
│   ├── local
│   │   ├── AppDatabase.kt
│   │   ├── Converters.kt
│   │   ├── daos
│   │   │   
│   │   └── entities
│   ├── remote
│   │   ├── api and data from the net
│   │   └── data from the backend
│   │   
│   └── repositories (place where all the data are collected)
│       
├
├── models
│   └── items and data class
├── ui
│   ├── fragments
│   │   ├── home
│   │   │   ├──  view model 
│   │   │   └──  fragment
│   │   ├── news
│   │   │   ├── 
│   │   │   └── 
│   │   ├── discuss
│   │   │   ├── 
│   │   │   └── 
│   │   ├── entertainment
│   │   │   ├── 
│   │   │   └── 
│   │   ├── profile
│   │   │   ├── 
│   │   │   └──
│   │   │  
│   └── adapters
│       ├── 
│       └── 
└── utils
    ├──  useful function 
    ├──  constants    
```
10 directories, 40 files


