### Muhammad Zaid

React Native & Expo engineer based in Lahore, Pakistan. I ship production iOS and Android apps end to end, and I go below the JavaScript layer when the product needs it: background location, native iOS extensions, Nitro modules, and gesture-driven UI on Reanimated.

**Open to** full-time and contract React Native roles, remote.

---

#### Apps I've built

**GigFlow: For Gig Workers**  
[App Store](https://apps.apple.com/us/app/gigflow-for-gig-workers/id6745483823) · [Google Play](https://play.google.com/store/apps/details?id=com.orcava.gigflowapp)  
Earnings, expense and mileage app for rideshare and delivery drivers. Mobile engineer at Techshires, 2025.

- **Automatic mileage tracking:** detects drives from speed in the background, records trips while the app is closed, fills in start and end addresses, and lets drivers swipe to mark each trip as work or personal for tax deductions.
- **Gig-platform earnings sync:** connected drivers' Uber/DoorDash-style accounts through Argyle, including the Android-specific integration fixes.
- **Income and expense tracking:** charts, categories, and timezone-correct reporting; replaced hand-rolled date logic with dayjs.
- **Monetization:** RevenueCat subscriptions with Superwall paywalls, trial-expiry flow, plus referral rewards and credits.
- **Release infrastructure:** Firebase phone auth, Expo OTA updates with an in-app update banner, Sentry, separate dev/prod environments, and 7 languages.

`Expo` `TypeScript` `Background Geolocation` `Argyle` `RevenueCat` `Superwall` `TanStack Query` `Zustand`

**WPF**  
[App Store](https://apps.apple.com/us/app/wpf/id6477957146) · [Google Play](https://play.google.com/store/apps/details?id=com.ofm.coachingcentral)  
Fitness coaching app with workout plans, challenges, community chat and health tracking. Mobile engineer at Techshires.

- **Workout state architecture:** persisted Zustand stores for exercises, the active workout and workout settings, split into state and actions, with hydration tracking so an in-progress workout survives an app restart.
- **Dynamic muscle illustration:** an SVG body map in the exercise instructions bottom sheet that highlights each exercise's primary muscle and its secondary muscles in different shades.
- **Workout timers:** a rest timer between sets that stays accurate in the background (timestamp-based), sends a "rest over" notification with vibration, can be extended mid-rest, and picks the rest length from the user's rep-range settings. Also countdown timers for time-based exercises.

`React Native` `Expo` `Zustand` `react-native-svg` `Expo Notifications` `Turborepo`

**Social community app** · *client project, launching soon*  
Community app with a social feed, clubs, direct messages and events. Lead mobile developer; also contributed to the Python backend.

- **Real-time messaging:** WebSocket DMs and group chat with reconnection handling, threaded replies, @mentions, pinning, and photo/video messages.
- **Hub feed:** media posts with comments, reactions, Q&A cards, contests and a billboard; optimistic updates throughout.
- **Moderation:** staff role that can remove content and suspend users, enforced on the server.
- **Platform currency:** upgraded to Expo SDK 58 and iOS 27, and adapted layouts for iPhone Duo and resizable windows.
- **Extras:** speech-to-text input, deep links, follow/friends graph, push notifications, Sentry.

`Expo SDK 58` `React Native 0.88` `WebSockets` `Legend List` `Uniwind` `TanStack Query`

---

#### Open source

**[Quran Lock](https://github.com/M-Zaid-Tayyab/QuranLock)**: iOS app that blocks distracting apps until the user completes their daily Quran reading. Three native Screen Time extensions (Device Activity monitor, Shield configuration, Shield action) wired into an Expo app; offline Quran data in SQLite; Nitro Modules; Convex backend.

**[react-native-image-compare-slider](https://github.com/M-Zaid-Tayyab/react-native-image-compare-slider)**: before/after image slider on [npm](https://www.npmjs.com/package/react-native-image-compare-slider).

---

#### Contact

[Portfolio](https://portfolio-nine-livid-77.vercel.app) · [LinkedIn](https://linkedin.com/in/muhammad-zaid-0a897b218/) · zaidtayyab1@gmail.com
