# Travel Advisor - React JS

Link to website: [Travel Advisor](https://travel-advisor-reactjs.netlify.app/)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/NishitShah18)

![Travel Companion App with React JS](https://user-images.githubusercontent.com/71302066/174569416-9e8250a9-87ef-49f4-be4a-f077196fe12f.png)

## ⚠️ Before you start

1. Make sure **Git** and **NodeJS** is installed
2. **Yarn** is faster than Npm. So use [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/).
3. Create .env.local file in root folder.
4. Contents of **.env.local**

```
REACT_APP_GOOGLE_MAP_API_KEY="XXXXXXXXXXXXXXXXXX"
REACT_APP_RAPID_API_KEY="XXXXXXXXXXXXXXXXXXXXX"
```

5. Go, to [Google Cloud Developers Console](https://console.cloud.google.com/projectcreate) and create a project.

![create a project](https://user-images.githubusercontent.com/71302066/174559275-458bbcec-6997-41f0-b359-1139e00fc759.png)

6. Once you created the project, make sure to select it from Header section.

![select your project](https://user-images.githubusercontent.com/71302066/174560599-92b3395c-9f43-4b42-a618-4151776b192d.png)

7. From Sidebar, Go to APIs & Services > Credentials > Create Credentials > **API Key**

![create api key](https://user-images.githubusercontent.com/71302066/174561372-6907aaf6-c538-46df-bd9e-6dfa08b9dd35.png)

8. Now click on **SHOW KEY** to get your `REACT_APP_GOOGLE_MAP_API_KEY`.

9. Now, to setup Travel Advisor and Weather API, go to [Rapid API Website](https://rapidapi.com/) and create an account.

10. Enable these two APIs for travel and weather data: [API 1: Travel Advisor](https://rapidapi.com/apidojo/api/travel-advisor/) and [API 2: Open Weather Map](https://rapidapi.com/community/api/open-weather-map/).

11. After enabling you can get your API Keys and paste them in `.env.local` file in `REACT_APP_RAPID_API_KEY`.

**NOTE:** Make sure you don't share these keys publicaly.

## 📌 How to use this App?

1. Clone this **repository** to your local computer.
2. Open **terminal** in root directory.
3. Type and Run `yarn install`.
4. Once packages are installed, type and run `yarn start`
5. Now app is fully configured and you can start using this app

## 📃 Built with

[<img src="https://media3.giphy.com/media/ln7z2eWriiQAllfVcn/200w.webp" width="100">](https://www.javascript.com/)
[<img src="https://i.giphy.com/media/eNAsjO55tPbgaor7ma/200w.webp" width="100">](https://reactjs.org/)

[<img src="https://img.shields.io/badge/Google%20Maps-4285F4?logo=googlemaps&logoColor=fff&style=flat" width="100" height="26">](https://developers.google.com/maps)
[<img src="https://user-images.githubusercontent.com/71302066/174567516-824b1967-5954-4ac7-9446-14a3b2ab825d.svg" alt="Rapid API" width="100">](https://rapidapi.com/)
