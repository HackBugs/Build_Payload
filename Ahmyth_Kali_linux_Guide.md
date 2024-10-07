Here’s your content formatted in Markdown:

```markdown
# Prerequisites

## Step 0
Update your package lists:
```bash
sudo apt update
```

## Step 1
Install Java 11 Development Kit (Required for Decompiling, Building, and Signing):
```bash
sudo apt-get install openjdk-11-jdk* -y
```

### Step 1.2
Change Java Version:
```bash
sudo update-alternatives --config java
```

### Step 1.3
Check Java Version:
```bash
java -version
```

## Step 2
Install NodeJS & npm (Required to run the Application):
```bash
sudo apt-get install nodejs npm -y
```

## Step 3
Install Zipalign (Required for Signing):

- Watch Video:

If you encounter any errors while installing Zipalign, fix them by running the following command:
```bash
sudo apt-get install android-libandroidfw android-liblog android-libutils libzopfli1
```

## Step 4
Install Ahmyth: Watch Video
```

You can copy this Markdown text into any Markdown editor or viewer to see the formatted output. Let me know if you need any changes!
