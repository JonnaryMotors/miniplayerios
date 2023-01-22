# miniplayerios
Implementing react-native-track-player with Expo including lock screen for iOS

As stated in the title, the purpose of this prototype is to provide all the information you need to display a music player on the lock screen.
Background story (you can skip that):
I searched for a solution for my personal audio project and came across two posts. The first said that ‘You can now use React Native Music Control with Expo.’ (https://expo.canny.io/feature-requests/p/react-native-music-control). All you need to do is creating a custom development client for your Expo app, install React Native Music Control and enable audio playback in background via your app.json.
The second post (same author) was very similar: ‘You can now use React Native Track Player with Expo.’ (https://expo.canny.io/feature-requests/p/audio-playback-in-background).  Here again, all you need to do is a custom development client for your Expo app, install React Native Track Player and enable audio playback in background via your app.json. Finishing with ‘And don't forget to register a playback service’.
I didn’t know about the possibility of create a development build with Expo. Using react-native-track-player didn’t require an additional package, therefore I made my choice, even if I found peculiar that the link for the app.json was referring the expo-av implementation – an alternative to the react-native-track-player. After struggling a little to implement it in my project (just like many other in the community), I finally found few hints in the Expo forums (https://forums.expo.dev/t/expo-react-native-track-player/62714). 
I decided to publish this prototype solution to ease the process for others - and here it is.
Note: I even asked some help to ChatGPT, the answer was positive but without details – no more than the two posts.
