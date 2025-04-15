# build_scripts_tulip
Redmi Note 6 Pro(Tulip) Build Scripts

## Tulip Build Instructions

#### Prerequisites
Install the necessary dependencies:
```
bash
sudo apt update && sudo apt install -y openjdk-11-jdk git-core gnupg flex bison gperf build-essential \
zip curl curl zlib1g-dev gcc-multilib g++-multilib libc6-dev-i386 lib32ncurses5-dev x11proto-core-dev \
libx11-dev lib32z1-dev libgl1-mesa-dev libxml2-utils xsltproc unzip fontconfig
```


# For Crave

• EvolutionX
```
crave run --clean --no-patch -- "curl -v https://raw.githubusercontent.com/DarkKiller28/build_scripts_tulip/main/evo_a15.sh | bash"
```

• YAAP
```
crave run --clean --no-patch "curl -v https://raw.githubusercontent.com/DarkKiller28/build_scripts_tulip/main/yaap_a15.sh | bash"
```
