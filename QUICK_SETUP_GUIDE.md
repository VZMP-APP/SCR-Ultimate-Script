# 🚀 SCR Autopilot V7 - Quick Setup Guide

## ⚡ 5-Minute Setup

### Step 1: Copy the Script ✂️
1. Open `scr_autopilot_v7_ultimate.lua`
2. Select all text (Ctrl+A / Cmd+A)
3. Copy to clipboard (Ctrl+C / Cmd+C)

### Step 2: Execute 🎮
1. Open Roblox and join Stepford County Railway
2. Spawn a train and enter the driver's cab
3. Open your executor (Synapse, Script-Ware, etc.)
4. Paste the script (Ctrl+V / Cmd+V)
5. Click "Execute" or press F6

### Step 3: Wait for Boot Screen 🖥️
- You'll see a cyan-colored boot screen
- Background image will load
- System initialization messages will appear
- Wait for "Tap anywhere to continue"
- Tap/click anywhere to proceed

### Step 4: Select Train Profile 🚂
1. GUI opens on "PROFILES" tab by default
2. Click on your train type:
   - Express: 115-125 mph trains
   - Connect: 100 mph trains
   - Metro/Waterline/AirLink: 80-100 mph
3. Selected profile shows "● ACTIVE"
4. Autopilot starts immediately!

### Step 5: (Optional) Setup Music 🎵
1. Click "MUSIC" tab
2. Default repository is already loaded
3. Click "LOAD" button
4. Click any song to play
5. Use player controls as needed

### Step 6: (Optional) Custom Background 🖼️
1. Click "BACKGROUND" tab
2. Either:
   - Enter custom image URL, or
   - Click a preset background button
3. Click "APPLY"
4. Background changes instantly

---

## 🎯 Quick Controls Reference

### Navigation Tabs (Left Sidebar)
- **▶ PROFILES** - Select train type
- **⚙ AUTOMATION** - Auto features
- **♪ MUSIC** - Music player
- **◈ BACKGROUND** - Custom backgrounds
- **◆ SETTINGS** - System controls
- **☰ CHANGELOG** - Update history

### Window Controls (Top Right)
- **× Red Button** - Close script
- **− Yellow Button** - Minimize/expand
- **↻ Left Button** - Recenter GUI

### Music Controls
- **⏮ PREV** - Previous song
- **⏸ PAUSE** - Pause/resume
- **⏹ STOP** - Stop playback
- **⏭ NEXT** - Next song

---

## 🔧 Common Settings

### For Express Trains (11 cars, 115 mph)
✅ Select: "Express | 11 Cars | MAX 115 MPH"

### For Connect Services (R039, R004)
✅ Select: "Connect | R039 + R004"

### For Metro/Local Services
✅ Select: "Metro | Empty"

### Enable Auto-Route
1. Go to "AUTOMATION" tab
2. Toggle "Auto Next Leg" ON
3. Every 10 seconds it auto-progresses

### Prevent AFK Kick
1. Go to "AUTOMATION" tab
2. Toggle "AntiAFK System" ON
3. You won't get kicked for inactivity

---

## 📱 Mobile vs Desktop

### Mobile Layout
- Compact 70px sidebar
- Icons only (no text labels)
- Touch-optimized buttons
- Smaller fonts
- Gesture support

### Desktop Layout
- Wide 220px sidebar
- Icons + text labels
- Mouse hover effects
- Larger fonts
- Drag functionality

---

## ⚠️ Troubleshooting Quick Fixes

**Problem: Script won't execute**
- Solution: Check executor supports required functions
- Required: HttpGet, writefile, isfile, asset loader

**Problem: Autopilot not working**
- Solution: Make sure profile shows "● ACTIVE"
- Must be in driver's cab with DriveGui visible

**Problem: Music won't play**
- Solution: Click "LOAD" button first
- Wait for "X songs found" message
- Then click a song

**Problem: GUI disappeared**
- Solution: Script may have closed
- Re-execute the script

**Problem: GUI off-screen**
- Solution: Click the ↻ (recenter) button on left

---

## 🎨 Customization Examples

### Adding Your Own Music
1. Create GitHub repo with MP3 files
2. Get the repo URL (must include /tree/branch/)
3. Example: `https://github.com/user/repo/tree/main/music`
4. Paste in MUSIC tab URL field
5. Click LOAD

### Using Your Own Background
1. Upload image to GitHub repo (.jpg or .png)
2. Get raw file URL
3. Example: `https://raw.githubusercontent.com/user/repo/main/bg.jpg`
4. Paste in BACKGROUND tab
5. Click APPLY

---

## 💡 Pro Tips

1. **Save Battery (Mobile)**: Close other apps while using
2. **Better Performance**: Lower Roblox graphics settings
3. **Quick Stop**: Click active profile again to disable
4. **Switch Profiles**: Can change mid-route safely
5. **Music Preload**: Songs cache after first play
6. **Background Testing**: Try presets before custom URLs

---

## 📞 Need Help?

- Check the full README for detailed information
- Visit: github.com/VZMP-APP/SCR-Autopilot
- Created by: VZMP.APP

---

**🎉 You're all set! Enjoy automated train driving!**

*Remember: Always monitor the script and drive responsibly*
