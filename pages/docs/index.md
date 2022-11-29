---
title: Watchful
---

# Welcome

{++Watchful++} is an `Android`/`WearOs` app that should help you to keep an eye on your daily app usage.

<figure markdown>
![Image title](.//assets/images/watchful_logo_v2_round.png){width="150"}
</figure>

## Features

### App Usage Overview:

<figure markdown>
  ![Image title](.//assets/gifs/phone_usage.gif){ width="300" loading=lazy } 
  <figcaption>Image caption</figcaption>
</figure>

provided information in overview:

- daily total time spent in apps
- daily total unlocks
- when did you use those apps

detail app view:

- when did you use the app today
- how much time did you spend in the app during the last weeks
- did you trigger alarms today?

### Merge your usage data merged with your health data

<figure markdown>
![Image title](.//assets/gifs/phone_health.gif){  width="300" loading=lazy} 
  <figcaption>Image caption</figcaption>
</figure>

today's health + usage data:

- heart rate
- steps
- sleep
- app usage

#### Create reminders to seize using apps

<figure markdown>
![Image title](.//assets/gifs/phone_alarms.gif){  width="300" loading=lazy} 
  <figcaption>Image caption</figcaption>
</figure>

- create, update and delete alarms for apps
- app selection is based of the 15 most used apps from the last 2 weeks
- alarm overview displays today's usage in respect to the alarms limit

### Open Data for your own analysis

an export function to gather data from various sources as CSV in a zip file:

- database:
  - usage-log table (persists usage data)
  - alarm-log table (persists alarm evenets)
  - alarm-change-log table (persists changes to alarm entities)
- google fit, exports last 2 weeks of:
  - heart rate (1 file per day in 1 min resolution)
  - steps (1 file per day in 1 min resolution)
  - sleep data (1 file)

<figure markdown>
![Image title](.//assets/gifs/phone_export.gif){  width="300" loading=lazy} 
  <figcaption>Image caption</figcaption>
</figure>

## WearOS Companion App

### watchface

core functionality of the wear app is it's watchface:

<figure markdown>
![Image title](.//assets/screenshots/wearable_v0.1/watchface.png){  width="300" loading=lazy} 
  <figcaption>Image caption</figcaption>
</figure>

### overview app

there is a more detailed overview about one's app usage provided through this companion app:

- only the top 5 apps are visible here

<figure markdown>
![Image title](.//assets/screenshots/wearable_v0.3/app_list.png){  width="300" loading=lazy} 
  <figcaption>Image caption</figcaption>
</figure>

### alarm activity

- gets "started" on the phone through a background worker checking alarm limits
  - with information about the app that triggered it
- color-theme of the alarm depends on the app color

<figure markdown>
![Image title](.//assets/gifs/watch_alarm.gif){  width="300" loading=lazy} 
  <figcaption>Image caption</figcaption>
</figure>
