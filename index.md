## APP Features 

#### usage overview:

<img src=".//gifs/phone_usage.gif" width="260" />

provided information in overview:
- daily total time spent in apps
- daily total unlocks
- when did you use those apps

detail app view:
- when did you use the app today
- how much time did you spend in the app during the last weeks
- did you trigger alarms today?


#### health data

<img src=".//gifs/phone_health.gif" width="260" />

today's health + usage data:
- heart rate
- steps
- sleep
- app usage

##### alarm control

<img src=".//gifs/phone_alarms.gif" width="260" />

- create, update and delete alarms for apps
- app selection is based of the 15 most used apps from the last 2 weeks
- alarm overview displays today's usage in respect to the alarms limit


#### data export

an export function to gather data from various sources as CSV in a zip file:
- database:
  - usage-log table (persists usage data)
  - alarm-log table (persists alarm evenets)
  - alarm-change-log table (persists changes to alarm entities)
- google fit, exports last 2 weeks of:
  - heart rate (1 file per day in 1 min resolution)
  - steps (1 file per day in 1 min resolution)
  - sleep data (1 file)


<img src=".//gifs/phone_export.gif" width="260" />

### wear OS

#### watchface
core functionality of the wear app is it's watchface:

<img src=".//screenshots/wearable_v0.1/watchface.png" width="260" />

#### overview app
there is a more detailed overview about one's app usage provided through this companion app:
- only the top 5 apps are visible here

<img src=".//screenshots/wearable_v0.3/app_list.png" width="260" />

#### alarm activity
- gets "started" on the phone through a background worker checking alarm limits
  - with information about the app that triggered it
- color-theme of the alarm depends on the app color

<img src=".//gifs/watch_alarm.gif" width="260" />


