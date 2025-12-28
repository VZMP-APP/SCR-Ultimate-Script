# 🚂 SCR Autopilot Terminal V7.0 ULTIMATE EDITION

## ✨ Complete Redesign with Modern Features

### 🎨 What's New in V7.0

#### 🖼️ **Custom Background System**
- **GitHub URL Support**: Load background images directly from GitHub repositories
- **Auto-Resizing**: Images automatically scale to fit the GUI perfectly
- **Preset Backgrounds**: 4 pre-configured background options
- **Boot Screen Integration**: Background appears during loading screen
- **Real-time Preview**: See changes instantly when applying new backgrounds

#### 🎵 **Enhanced RawPlayer Browser**
- **GitHub Repository Integration**: Load entire music libraries from GitHub
- **Smart Caching**: Downloaded songs are cached locally for faster playback
- **Playlist Management**: Browse and select songs from a scrollable list
- **Auto-Next**: Automatically plays the next song when current ends
- **Bass Boost**: Enhanced equalizer for deeper audio
- **Loop Mode**: Repeat current song or playlist
- **Progress Bar**: Visual playback progress with time display
- **Full Controls**: Previous, Pause/Play, Stop, Next buttons

#### 🎨 **Modern Glass Morphism UI**
- **Frosted Glass Effect**: Semi-transparent panels with blur effects
- **Gradient Overlays**: Beautiful color transitions throughout
- **Smooth Animations**: All UI elements animate smoothly
- **Glow Effects**: Neon-style borders and accents
- **Scanline Overlay**: Retro-futuristic visual effect
- **Shadow Depth**: 3D-style depth with shadows

#### 📱 **Adaptive Responsive Design**
- **Mobile Optimized**: Compact layout for mobile devices
- **Desktop Enhanced**: Expanded layout for larger screens
- **Auto-Detection**: Automatically detects device type
- **Touch Support**: Full touch gesture support for mobile
- **Drag & Drop**: Move GUI anywhere on screen
- **Recenter Button**: Quick return to center position

### 🚀 Core Features

#### ⚡ **Train Profiles** (6 Pre-configured)
1. **Express | 11 Cars | MAX 115 MPH**
   - Max Speed: 115 mph
   - Safe Stop: 60 mph
   - Stop Distance: 0.60

2. **Connect | R039 + R004**
   - Max Speed: 100 mph
   - Safe Stop: 40 mph
   - Stop Distance: 0.35

3. **Metro | Empty**
   - Max Speed: 80 mph
   - Safe Stop: 35 mph
   - Stop Distance: 0.30

4. **Waterline | R018**
   - Max Speed: 100 mph
   - Safe Stop: 40 mph
   - Stop Distance: 0.35

5. **AirLink | Empty**
   - Max Speed: 90 mph
   - Safe Stop: 38 mph
   - Stop Distance: 0.32

6. **Express | 80x**
   - Max Speed: 125 mph
   - Safe Stop: 65 mph
   - Stop Distance: 0.55

#### ⚙️ **Automation Systems**
- **Auto Next Leg**: Automatically progress to next route segment every 10 seconds
- **AntiAFK System**: Prevents AFK kick by simulating user activity
- **Smart Speed Control**: Automatically adjusts speed based on signals and distance
- **Signal Detection**: Reads and responds to all signal types (Proceed, Caution, Precaution, Danger)
- **Emergency Stop**: Automatic stopping at danger signals and end of route

#### 🎵 **Music Player (RawPlayer Browser)**
- **GitHub Integration**: Load songs from any GitHub repository
- **Supported Format**: MP3 files only
- **Playlist Features**:
  - Scrollable song list
  - Click to play any song
  - Visual progress bar
  - Time display (current/total)
  - Auto-next when song ends
- **Audio Controls**:
  - Previous track
  - Pause/Resume
  - Stop playback
  - Next track
  - Loop toggle
  - Bass boost toggle
- **Default Repository**: Pre-loaded with VZMP music collection

#### 🖼️ **Custom Backgrounds**
- **URL Input**: Paste any GitHub image URL
- **Supported Formats**: JPG, PNG
- **Preset Options**:
  1. Default
  2. Cyberpunk City
  3. Night Train
  4. Abstract Neon
- **Features**:
  - Auto-download and cache
  - Real-time preview
  - Boot screen integration
  - Adaptive sizing

### 🎯 Usage Instructions

#### 📥 Installation
1. Copy the script: `scr_autopilot_v7_ultimate.lua`
2. Execute in your Roblox executor
3. Wait for boot screen to complete
4. Tap/click anywhere to start

#### 🎮 Basic Operation

**Step 1: Select a Train Profile**
1. Navigate to "PROFILES" tab (default)
2. Click on your desired train profile
3. Profile will highlight and show "ACTIVE" status
4. Autopilot will automatically start

**Step 2: Enable Automation (Optional)**
1. Navigate to "AUTOMATION" tab
2. Toggle "Auto Next Leg" for automatic route progression
3. Toggle "AntiAFK System" to prevent kick

**Step 3: Setup Music (Optional)**
1. Navigate to "MUSIC" tab
2. Enter GitHub repository URL (or use default)
3. Click "LOAD" to fetch song list
4. Click any song to play
5. Use controls to manage playback

**Step 4: Customize Background (Optional)**
1. Navigate to "BACKGROUND" tab
2. Enter image URL or select a preset
3. Click "APPLY" to change background
4. Image will appear on main GUI and boot screen

#### 🔧 Settings & Management
- **Minimize**: Click yellow button to collapse GUI
- **Close**: Click red button to terminate script
- **Recenter**: Click circular arrow button to center GUI
- **Drag**: Click and hold title bar to move GUI

### 🎨 Design Features

#### Color Scheme
- **Primary**: Cyan/Teal (#00FFAA)
- **Secondary**: Sky Blue (#64C8FF)
- **Accent**: Pink/Magenta (#FF64B4)
- **Warning**: Orange (#FFB432)
- **Danger**: Red (#FF4664)
- **Success**: Green (#50FF78)

#### Visual Effects
- Glass morphism with frosted blur
- Gradient overlays on all panels
- Glowing borders and strokes
- Smooth fade transitions
- Hover animations
- Click feedback
- Progress indicators
- Scanline overlay

#### Typography
- **Headers**: Gotham Bold
- **Body Text**: Gotham Medium
- **Code/Data**: Roboto Mono

### 📱 Device Compatibility

#### Mobile Devices
- Compact sidebar (70px)
- Smaller font sizes (9-14px)
- Touch-optimized buttons
- Reduced spacing
- Scalable text elements
- Gesture support

#### Desktop/Tablet
- Expanded sidebar (220px)
- Larger font sizes (11-18px)
- Mouse hover effects
- Increased spacing
- Full labels visible
- Drag functionality

### ⚡ Performance

- **Optimized**: Efficient code structure
- **Cached**: Music and images cached locally
- **Smooth**: 60 FPS animations
- **Responsive**: Instant UI feedback
- **Stable**: Error handling throughout

### 🔐 Safety Features

- **Script Validation**: Checks for required executor functions
- **Error Handling**: Try-catch blocks prevent crashes
- **Clean Termination**: Properly disconnects all events
- **No Memory Leaks**: Destroys unused objects
- **Safe Defaults**: Conservative speed settings

### 📋 Requirements

- **Executor**: Must support:
  - `game:HttpGet()` - For downloading files
  - `writefile()` / `isfile()` - For caching
  - `getcustomasset()` or `getsynasset()` - For loading assets
  - `VirtualInputManager` - For autopilot controls
- **Game**: Stepford County Railway on Roblox
- **Internet**: Required for music and background loading

### 🐛 Troubleshooting

**Issue**: Boot screen won't dismiss
- **Solution**: Tap/click anywhere on screen

**Issue**: Background image won't load
- **Solution**: 
  - Verify URL is correct
  - Ensure image is JPG or PNG
  - Check internet connection
  - Try a preset background

**Issue**: Music won't play
- **Solution**:
  - Verify repository URL is correct
  - Ensure repository contains MP3 files
  - Check executor supports audio
  - Try default music URL

**Issue**: Autopilot not working
- **Solution**:
  - Ensure a profile is selected (shows "ACTIVE")
  - Check you're in a train cab
  - Verify DriveGui is visible
  - Re-execute script if needed

**Issue**: GUI off-screen
- **Solution**: Click the recenter button (↻) on left side of GUI

### 📊 Changelog Summary

**V7.0 ULTIMATE** (Current)
- Complete UI redesign
- Glass morphism effects
- Custom background system
- Enhanced RawPlayer integration
- Adaptive responsive design
- 15+ new features

**V6.0 MUSIC**
- RawPlayer music system
- GitHub repository support
- Music controls

**V6.0**
- Mobile support
- Touch controls
- Recenter button

### 🔗 Links

- **GitHub Repository**: github.com/VZMP-APP/SCR-Autopilot
- **Music Repository**: github.com/VZMP-APP/SCR-Script
- **Creator**: VZMP.APP

### ⚠️ Disclaimer

This script is for educational purposes. Use responsibly and be aware that:
- Automation may violate game Terms of Service
- Use at your own risk
- The creator is not responsible for any consequences
- Always be present and monitor the script

### 💡 Tips & Tricks

1. **Best Performance**: Close other Roblox GUIs for better FPS
2. **Quick Access**: Set up custom backgrounds before long sessions
3. **Music Playlist**: Create a GitHub repo with your favorite tracks
4. **Mobile Usage**: Use landscape mode for better visibility
5. **Profile Switching**: You can switch profiles mid-route
6. **Emergency Stop**: Click profile again to disable autopilot instantly

### 🎯 Future Plans

- Profile editor for custom train configurations
- Multiple music playlist support
- Background slideshow mode
- Custom color themes
- Route statistics tracking
- Achievement system

---

**Made with ❤️ by VZMP.APP**

*Enjoy your automated train driving experience! 🚂*
