ગુજરાતી પંચાંગ Live Wallpaper — Android Studio વગર APK બનાવવાની રીત

મહત્વપૂર્ણ:
- આ ZIP Android Studio project છે; APK પહેલેથી તૈયાર નથી.
- આ project માં GitHub Actions workflow ઉમેરેલ છે, જેથી GitHub ના cloud computer પર APK build કરી શકાય.
- Build સફળ થાય તો app-debug.apk GitHub Actions ના Artifacts માં મળશે.
- APK અહીંથી build/test કરેલી નથી; સફળ build અને ફોન પર wallpaper service કામ કરે છે તેની ખાતરી નથી.

સરળ પગલાં:
1. GitHub.com પર sign in કરો અને નવું repository બનાવો (ઉદાહરણ: GujaratiPanchangLiveWallpaper).
2. આ ZIP તમારા કમ્પ્યુટર પર Extract કરો.
3. Extract થયેલા project ની અંદરની બધી files/folders repository માં upload કરો. ખાસ કરીને .github/workflows/build-apk.yml પણ upload થવી જોઈએ. જો .github folder દેખાતો ન હોય તો Windows File Explorer માં View > Show > Hidden items ચાલુ કરો.
4. GitHub repository ખોલો > Actions tab પસંદ કરો.
5. “Build Gujarati Panchang APK” workflow પસંદ કરો > Run workflow દબાવો.
6. Build પૂર્ણ થયા પછી workflow run ખોલો. નીચે Artifacts માં “GujaratiPanchangLiveWallpaper-APK” download કરો.
7. ZIP extract કરો; અંદર app-debug.apk મળશે. તેને તમારા Android ફોનમાં મોકલી install કરો. અજાણ્યા સ્ત્રોતથી install માટે ફોન પર મંજૂરી માંગે તો સાવચેતીથી મંજૂરી આપો.
8. App ખોલો > Live Wallpaper વિકલ્પ > wallpaper preview > Set wallpaper. Home screen અને Lock screen બંનેનો વિકલ્પ ફોનના Android/launcher પર આધારિત છે.

જો Actions માં workflow ન દેખાય:
- ખાતરી કરો કે .github/workflows/build-apk.yml repository માં અપલોડ થયેલી છે.
- Repository ના Actions tab માં workflows enable થયાં છે તે તપાસો.

ફાઇલમાં સામેલ ઓળખ વિગતો:
સંકલન: શ્રી આનંદભાઈ મોદી
સીઆરસી કો ઓર્ડિનેટર આદ્યશક્તિ ઇન્દિરા
મોબાઇલ: 9427914014
