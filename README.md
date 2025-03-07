<!-- README for awaisshafique/awaisshafique -->

# Hi there, I'm **Muhammad Awais Shafique**! 👋

I’ve been **passionately working** in the game development industry for **7+ years**, specializing in the **Unity 3D** engine. My journey has allowed me to **develop and release multiplatform games**—across **Amazon**, **Google Play**, **Apple App Store**, **CrazyGames**, and more—spanning diverse genres like **action**, **simulation**, **idle**, **hyper-casual**, and even **metaverse** projects. Beyond coding, I’m deeply involved in **advanced analytics**, **plugin integrations**, and **team leadership**, ensuring each title provides a seamless, engaging experience.

---

## ⚡ Quick Facts About Me

- **Hands-On Experience**:  
  - Integrating various **analytics SDKs** and **ad network SDKs**  
  - Optimizing game performance for **mobile** devices  
  - Reducing **WebGL build sizes** through specialized methods and techniques  
  - **Improving game vitals** and **stabilizing builds** across stores like Google Play and App Store  

- **Technical Focus**:  
  - **Player retention**, **feature optimization**, and **workflow improvements**  
  - Proficient in **AR/VR** and **WebGL** environments  
  - Developing **custom shaders** for unique visual effects  
  - **Making games from scratch**, including custom systems and tools  

- **Current Exploration**:  
  - Mastering **Unity’s newest features**  
  - Diving deeper into **advanced game analytics** and **retention analysis** for a better player experience  
  - Exploring **ML-Agents** and various **AI tools** to improve efficiency and gameplay  

- **Dev Approach**:  
  - Applying **SOLID principles** and **design patterns**  
  - Optimizing for **low-end devices**  
  - Managing teams and projects with **Trello** and **Jira**  

- **Fun Fact**:  
  - I’ve contributed to **popular hyper-casual games**  
  - Helped **build a metaverse** platform, pushing the boundaries of interactive entertainment  

---

## 🛠 Tech & Tools

### Game Engines & Languages
![Unity](https://img.shields.io/badge/-Unity-000000?logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?logo=c-sharp&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-0095D5?logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)

### Editors & IDEs
![Rider](https://img.shields.io/badge/-Rider-000000?logo=rider&logoColor=white)
![Visual Studio](https://img.shields.io/badge/-Visual%20Studio-5C2D91?logo=visual-studio&logoColor=white)
![JetBrains](https://img.shields.io/badge/-JetBrains-000000?logo=jetbrains&logoColor=white)

### Graphics & Productivity
![GIMP](https://img.shields.io/badge/-GIMP-5C5543?logo=gimp&logoColor=white)
![Inkscape](https://img.shields.io/badge/-Inkscape-000000?logo=inkscape&logoColor=white)
![Photoshop](https://img.shields.io/badge/-Photoshop-31A8FF?logo=adobe-photoshop&logoColor=white)
![Illustrator](https://img.shields.io/badge/-Illustrator-FF9A00?logo=adobe-illustrator&logoColor=white)
![LibreOffice](https://img.shields.io/badge/-LibreOffice-18A303?logo=libreoffice&logoColor=white)

### Platforms & Stores
![Android](https://img.shields.io/badge/-Android-3DDC84?logo=android&logoColor=white)
![WebGL](https://img.shields.io/badge/-WebGL-990000?logo=webgl&logoColor=white)
![Google Play Store](https://img.shields.io/badge/-Google%20Play-414141?logo=google-play&logoColor=white)
![Apple App Store](https://img.shields.io/badge/-App%20Store-0D96F6?logo=app-store&logoColor=white)
![Amazon App Store](https://img.shields.io/badge/-Amazon%20Appstore-FF9900?logo=amazon&logoColor=white)
![Huawei Store](https://img.shields.io/badge/-Huawei%20AppGallery-FF0000?logo=huawei&logoColor=white)
![CrazyGames](https://img.shields.io/badge/-CrazyGames-333333?logoColor=white)
![YouTube Playables](https://img.shields.io/badge/-YouTube%20Playables-FF0000?logo=youtube&logoColor=white)

### Services & Other Tools
![Google Play Services](https://img.shields.io/badge/-Google%20Play%20Services-34A853?logo=google-play&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?logo=firebase&logoColor=white)
![Photon Fusion](https://img.shields.io/badge/-Photon%20Fusion-0080FF?logo=photon-engine&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/-Windows%20Terminal-4D4D4D?logo=windows-terminal&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white)

---

## Unity Addressables: Key Highlights

- **What They Are**  
  - A labeling system within Unity that streamlines the process of loading and unloading game assets on demand.

- **Why They’re Essential**  
  1. **Faster Start-Up**  
     - Only load core game elements initially—crucial when dealing with size limits (often 15 MB) on web platforms.
  2. **Optimized Memory Usage**  
     - Free up memory by unloading assets once they’re no longer needed.
  3. **Efficient Updates**  
     - Update or replace specific asset bundles instead of rebuilding the entire project.
  4. **Organized Asset Management**  
     - Prevent duplicate files and track dependencies automatically.

- **Ideal for Web Platforms**  
  - **Minimal Initial Download**: Speed up player access by loading extra content later.
  - **On-Demand Asset Streaming**: Large levels, textures, or audio can be fetched asynchronously.
  - **Better Retention**: Rapid loading keeps players engaged.

- **Workflow Overview**  
  1. **Label Assets**: Assign tags (e.g., “Level1” or “Enemies”).
  2. **Bundle Creation**: Unity groups assets under these labels.
  3. **Load As Needed**: Use `Addressables.LoadAssetAsync()` to bring them in at runtime.
  4. **Unload to Save Memory**: Remove bundles not in use.
  5. **Remote Hosting (Optional)**: Keep large bundles on a server and download them selectively.

- **Practical Tips**  
  1. **Plan Asset Splits**: Decide which assets are essential for initial load.
  2. **Use Meaningful Labels**: Consistent naming conventions aid organization.
  3. **Monitor Performance**: Test on multiple devices and networks.
  4. **Leverage CI**: Automate bundle builds and uploads for quick patches.

- **Why It Makes a Difference**  
  - **Improved Performance**: Eliminates loading overhead for unnecessary assets.
  - **Scalability**: Easily incorporate additional content over time.
  - **Enhanced Player Experience**: Fast loading, smooth updates, and reduced file sizes.

---

## 🌐 Connect with Me

<p>
  <a href="https://www.linkedin.com/in/awais-shafique-832895124">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn Badge" />
  </a>
  <a href="mailto:awais.shafique71@outlook.com">
    <img src="https://img.shields.io/badge/-Email-0078D4?logo=microsoft-outlook&logoColor=white" alt="Email Badge" />
  </a>
</p>
