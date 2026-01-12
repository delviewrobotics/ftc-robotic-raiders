# FTC Robotic Raiders #22648 Website

## Image File Structure

Your images should be organized exactly like this:

```
images/
├── logo/
│   └── raiders_logo.png          ✅ Your team logo
│
├── home/
│   ├── team-photo.jpg            ✅ Team photo for homepage
│   └── robot-main.jpg            ✅ Robot photo for homepage
│
├── history/
│   ├── 2025-25-intothedeep.jpg   ✅ Current season robot
│   ├── 2023-24-centerstage.jpg   ✅ CENTERSTAGE season robot
│   └── 2022-23-powerplay.jpg     ✅ POWERPLAY season robot
│
├── awards/
│   └── connect-award.jpg         ✅ Connect Award photo
│
├── outreach/
│   ├── wesbrooke_communitycentre.jpg    ✅ Outreach event
│   ├── wesbrooke_communitycentre_2.jpg  ✅ Outreach event
│   ├── stemastery.png                   ✅ STEMastery event
│   └── bill_barbie_zoomcall.PNG         ✅ Zoom mentorship
│   
│   ⚠️ NOTE: delviews_physics_11.HEIC won't work in browsers!
│   Convert it to .jpg or .png first if you want to use it.
│
├── members/
│   ├── Petra Hammoser.jpg        ✅ Coach
│   ├── Rachel.png                ✅ Coach
│   ├── HAMMOSER_BJORN.jpeg       ✅ Team Captain
│   ├── Naim.png                  ✅ Graphic Designer
│   ├── DHANDA_JOBAN.jpeg         ✅ Documentation
│   ├── DAS_RISHAV.jpeg           ✅ Designer
│   ├── Abhinav.png               ✅ Member
│   ├── Withya.png                ✅ Member
│   ├── Aidan.jpg                 ✅ Member
│   └── Harshith.jpeg             ✅ Member (NEW!)
│
└── archive/                      (Extra images you're keeping)
```

## Uploading to GitHub

### Step 1: Upload HTML & CSS first
1. Go to your repo: github.com/delviewrobotics/ftc-robotic-raiders
2. Upload all HTML files and the css/ folder

### Step 2: Create images folder structure
1. Click "Add file" → "Create new file"
2. Type: `images/logo/raiders_logo.png`
3. This creates the folder structure

### Step 3: Upload images by folder
Upload images folder by folder:
1. `images/logo/` - Upload raiders_logo.png
2. `images/home/` - Upload team-photo.jpg, robot-main.jpg
3. `images/history/` - Upload all 3 robot photos
4. `images/awards/` - Upload connect-award.jpg
5. `images/outreach/` - Upload all outreach photos
6. `images/members/` - Upload all member photos

## Enable GitHub Pages

1. Go to Settings → Pages
2. Source: Deploy from branch
3. Branch: main
4. Folder: / (root)
5. Click Save
6. Wait 1-2 minutes
7. Visit: https://delviewrobotics.github.io/ftc-robotic-raiders

## Team Members on Website

| Name | Photo File | Role |
|------|------------|------|
| Petra Hammoser | `Petra Hammoser.jpg` | Coach |
| Rachel | `Rachel.png` | Coach |
| Björn Hammoser | `HAMMOSER_BJORN.jpeg` | Team Captain |
| Naim T. | `Naim.png` | Graphic Designer |
| Joban D. | `DHANDA_JOBAN.jpeg` | Documentation |
| Rishav D. | `DAS_RISHAV.jpeg` | Designer |
| Abhinav | `Abhinav.png` | Member |
| Withya | `Withya.png` | Member |
| Aidan | `Aidan.jpg` | Member |
| Harshith | `Harshith.jpeg` | Member (NEW!) |

## ⚠️ Important Notes

1. **HEIC files don't work** - Convert `delviews_physics_11.HEIC` to .jpg
2. **File names are case-sensitive** - `Naim.png` is different from `naim.png`
3. **Spaces in filenames** - `Petra Hammoser.jpg` has a space (that's fine)

## Editing the Website

To change team member info, edit `team.html`:
- Find the member's section
- Update name, role, or photo path

To add a new member, copy an existing member block and update:
```html
<div class="team-card">
    <div class="member-photo">
        <img src="images/members/NEWMEMBER.jpg" alt="New Member">
    </div>
    <h3>New Member Name</h3>
    <p class="role">Role</p>
</div>
```
