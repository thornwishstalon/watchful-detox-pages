## Allow `Watchful` access to read usage statistics

<!-- prettier-ignore-start -->
!!! note
    Since Android 10 app permissions have become stricter to the point, that special permissions need to be actively
    provided to apps through you. see [Android Developer Documentation](https://developer.android.com/about/versions/10/privacy/changes) for more information.

    So you neeed to manually give Watchful  permission to gain access to usage data ... sorry
<!-- prettier-ignore-end -->

Go to `Settings` > `Apps` > `Special app access` > `usage access`

<figure markdown>
![Image title](./../assets/screenshots/setup/setup_permissions.png){ loading=lazy width="300"}
  <figcaption>  Permit usage access for Watchful ✅ </figcaption>
</figure>

## Allow `Watchful` unrestricted battery usage

<!-- prettier-ignore-start -->
!!! note
    Android is keeping a sharp eye on battery consumption and thus tries to limit background worker. 
    Since `Watchful` needs to run several processes in the background to evaluate
    alarm states and synchronize your usage stats with the watch. 


<!-- prettier-ignore-end -->

To give `Watchful` unrestricted battery usage permission long-press the app' icon and press 'App info' and navigate to
`App battery usage` (see image below). Here please select the `Unrestricted` option.

<figure markdown>
![Image title](./../assets/screenshots/setup/unrestricted_battery_usage.png){ loading=lazy width="300"}
  <figcaption>  Permit unrestricted battery usage for Watchful ✅ </figcaption>
</figure>

<!-- prettier-ignore-start -->
!!! success
    Very nice! Not let's setup Watchful to access Google Fit!
<!-- prettier-ignore-end -->
