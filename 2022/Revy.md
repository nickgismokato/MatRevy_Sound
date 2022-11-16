# TODO
- [X] Create ```.md``` file
- [X] Write in all ```Midas M32``` Channels
- [ ] Write guide for the physical setup of sound
  - [ ] Write guide for table setup
- [ ] Write guide for basic routing and setup of the ```Midas M32``` mixer
- [ ] Write guide for extended routing and setup of the ```Midas M32``` mixer

# TOC

- [TODO](#todo)
- [TOC](#toc)
- [Revy stuff](#revy-stuff)
  - [Abbreviations](#abbreviations)
  - [Channels](#channels)
  - [Mix-bus Routing](#mix-bus-routing)
  - [Matrix Routing](#matrix-routing)
  - [Output Routing](#output-routing)
  - [PB16 Routing](#pb16-routing)
- [Physical Setup](#physical-setup)
  - [All components for stage setup](#all-components-for-stage-setup)
  - [All components for band setup](#all-components-for-band-setup)
  - [Explanation](#explanation)
  - [Setup Routing](#setup-routing)
    - [Mixer to StageBox](#mixer-to-stagebox)
      - [Requires](#requires)
      - [Setup](#setup)
      - [Bugs](#bugs)
    - [StageBox To Pre-Amps](#stagebox-to-pre-amps)
      - [Requires](#requires-1)
      - [Setup](#setup-1)
      - [Bugs](#bugs-1)
    - [StageBox To Band Monitor](#stagebox-to-band-monitor)
      - [Requires](#requires-2)
      - [Setup](#setup-2)
      - [Bugs](#bugs-2)
    - [StageBox To Stage Monitor](#stagebox-to-stage-monitor)
      - [Requires](#requires-3)
      - [Setup](#setup-3)
      - [Bugs](#bugs-3)
    - [Pre-Amp to Monitors](#pre-amp-to-monitors)
      - [Requires](#requires-4)
      - [Setup](#setup-4)
      - [Bugs](#bugs-4)
- [How-To Basic](#how-to-basic)
  - [Basic setup of ```Midas32```](#basic-setup-of-midas32)
  - [Routing](#routing)
  - [What is a ```mix-bus```](#what-is-a-mix-bus)
  - [How to set your ```mix-bus```](#how-to-set-your-mix-bus)
  - [Basic Recording](#basic-recording)
- [How-To Extended](#how-to-extended)
  - [Routing Extended](#routing-extended)
  - [What is ```Matrix```](#what-is-matrix)
  - [How to set your matrix](#how-to-set-your-matrix)
  - [Mixing/Mastering](#mixingmastering)
  - [Extended guide of recording.](#extended-guide-of-recording)

# Revy stuff

## Abbreviations

## Channels

|Channel|Instrument/Channel||Channel|Instrument/Channel||Channel|Instrument/Channel|
|:---:|:---:|---|:---:|:---|---|:---:|:---|
|1|```Kick```||17|```BMic``` 1||```Aux``` 1|```Aux``` 5 (AV L)|
|2|```Snare```||18|```BMic``` 2||```Aux``` 2|```Aux``` 6 (AV R)|
|3|```HiHat```||19|``` ```||```Aux``` 3|```User def``` 3 (```HS``` Red)|
|4|```HT```||20|``` ```||```Aux``` 4|```User def``` 4 (```HS``` Yellow)|
|5|```MT```||21|``` ```||```Aux``` 5|```User def``` 5 (```HS``` Green)|
|6|```FT```||22|``` ```||```Aux``` 6|```User def``` 6 (```HS``` Blue)|
|7|```OH```1||23|```EMic``` 1||```USB L```|``` ```|
|8|```OH```2||24|```EMic ``` 2||```USB R```|``` ```|
|9|```Bass```||25|```HH ```Red|||``` ```|
|10|```Guitar```||26|```HH ```Yellow|||``` ```|
|11|```Piano```||27|```HH ```Green|||``` ```|
|12|```Trumpet```||28|```HH ```Blue|||``` ```|
|13|```Alt Sax```||29|```HH ```Red White|||``` ```|
|14|```TenorSax```||30|```HH ```Yellow White|||``` ```|
|15|```SopranSax```||31|```HH ```Green White|||``` ```|
|16|```Violin```||32|```HH ```Blue White|||``` ```|
|

## Mix-bus Routing
|Bus Channel|Usage||Bus Channel|Usage|
|:---:|:---|---|:---:|:---|
|```Bus``` 1|Used for ```Matrix``` 1||```Bus``` 9|```Tenor``` + ```Sopran sax```|
|```Bus``` 2|Used for ```Matrix``` 2||```Bus``` 10|```OH```|
|```Bus``` 3|BackStage send||```Bus``` 11|```Toms```|
|```Bus``` 4| ||```Bus``` 12| |
|```Bus``` 5|```AV```||```Bus``` 13|```Effect```|
|```Bus``` 6|```HH```||```Bus``` 14|```Effect```|
|```Bus``` 7|```HS```||```Bus``` 15|```Effect```|
|```Bus``` 8|```EMic```||```Bus``` 16|```Effect```|
|

## Matrix Routing
|```Matrix```|Input|Usage|
|:---|:--|:---|
|1|```Bus``` 1|Left scene monitor|
|2|```Bus``` 2|Right scene monitor|
|3|||
|4|||
|5|||
|6|```Bus``` 6-8|Send to PB 15|
|

## Output Routing
|Channel|Output||Channel|Output|
|:---:|:---:|---|:---:|:---:|
|1|```Bus``` 3||9|``` Empty ```|
|2|``` Empty ```||10|``` Empty ```|
|3|``` Empty ```||11|``` Empty ```|
|4|``` Empty ```||12|``` Empty ```|
|5|``` Empty ```||13|``` Matrix 1 ```|
|6|``` Empty ```||14|``` Matrix 2 ```|
|7|``` Empty ```||15|``` Main L ```|
|8|``` Empty ```||16|``` Main R ```|
|

## PB16 Routing
|Channel|In||Channel|In|
|:---:|:---:|---|:---:|:---:|
|```PB``` 1|```Kick```||```PB``` 9|```Trumpet```|
|```PB``` 2|```Snare```||```PB``` 10|```Alt Sax```|
|```PB``` 3|```HH```||```PB``` 11|```Tenor``` + ```Sopran Sax``` (```Mixbus``` 9)|
|```PB``` 4|```Toms``` (```Mixbus``` 11)||```PB``` 12|```Violin```|
|```PB``` 5|```OH``` (```Mixbus``` 10)||```PB``` 13| ```BMic``` 1|
|```PB``` 6|```Bass```||```PB``` 14|```BMic``` 2|
|```PB``` 7|```Guitar```||```PB``` 15|```HH``` + ```HS``` + ```EMic```|
|```PB``` 8|```Klaver```||```PB``` 16|```AV``` L + ```AV``` R|
|

# Physical Setup

## All components for stage setup

|Components|Usage|own|
|:---|:---|:---:|
|Midas M32|A mixer| <input type="checkbox" /> |
|Midas M32 StageBox|Used as external inputs through ethernet for ```XLR``` band inputs|<input type="checkbox" />|
|2 X Pre-amps|Amplify the left + right main monitors|<input type="checkbox" />|
|2 X sub-woofer + 2 X monitor on rack|Main Stage monitors|<input type="checkbox" />|
|2 X Flying monitors + fly kit|Monitors to hang in the framework|<input type="checkbox" />|
|2 X Stage monitor|Monitors for actors and singers when they are on the scene|<input type="checkbox" />|
|```HH``` + ```HS``` Rack|Used for wireless mics|<input type="checkbox" checked />|
|

## All components for band setup
<input type="checkbox" checked />
<input type="checkbox" />

|Components|Usage|Own|
|:---|:---|:---:|
|Shure Beta 52A|Bass drum mic|<input type="checkbox" />|
|Short mic stand for 52A|Mic stand for 52A microphone|<input type="checkbox" />|
||||

## Explanation

## Setup Routing

### Mixer to StageBox

#### Requires
- Midas 32
- StageBox
- 1 Ethernet Cable (*Probably two for safety measure*)

#### Setup

**Can be done Before $\TeX\text{nik}$ get delivered and ```Scenen``` has been setup:**

> Run a Ethernet Cable or 2 From $\TeX\text{nik}$ down to lecture stage. The will be routed from a pipe installed in ```StUP``` 1.
>> If ```Scenen``` is allready set up, this job can be more difficult.
>
>> You can also run ```XLR``` Cables for light when you are already running you ethernet cables.

**Need Mixer and StageBox:**

>Insert Ethernet Cable in the mixers ```AES50``` A port and do the same for the StageBox.

You are now done

#### Bugs
> -Sometimes when turning on the mixer and then the StageBox, the all-mute button is stuck on the stage box.
> > Restarting the mixer while the StageBox is turned on should fix this.
>
>

### StageBox To Pre-Amps

#### Requires

- StageBox
- Pre-amps
- ```XLR``` cables equal to amount of pre-amps

#### Setup

> 1. Choose desired output on StageBox
>     - Choose what output should be left/right or Left/Left-sub/Right/Right-sub
> 2. Choose what pre-amp should be left/right
> 3. Plug female end of ```XLR``` cable to desired output channel on stage box
> 4. Run Cable and plug in the male end of ```XLR``` cable to pre-amp input.

#### Bugs

No know bugs

### StageBox To Band Monitor

#### Requires

#### Setup

#### Bugs


### StageBox To Stage Monitor

#### Requires

#### Setup

#### Bugs

### Pre-Amp to Monitors

#### Requires

#### Setup

#### Bugs

# How-To Basic

## Basic setup of ```Midas32```

## Routing

## What is a ```mix-bus```

Essentially this will sum up what a ```mix-bus``` is

>A ```mix-bus``` is a bus where you can send channels to it. From here you can route the ```mix-bus``` through effect or to specific outputs.

A ```mix-bus``` can allow one to choose which channels to send where without the need of really weird routing of the main channel.

**Important:** You CANNOT send a ```mix-bus``` to another ```mix-bus```.

## How to set your ```mix-bus```

There are two ways. We will only go through the correct way.

> 1. Press ```Select``` for the bus you want to configure
> 2. Press ```Fader Flip```
> 3. Turn up the faders of the channels you want to go, to your ```mix-bus```

## Basic Recording

# How-To Extended

## Routing Extended

## What is ```Matrix```

This is the definition of a ```Matrix```.

> A ```Matrix``` is a ```mix-bus``` but for other ```busses``` like a ```mix -bus```.

**Important:** You CANNOT send channels to the matrix. Only busses.

## How to set your matrix

I only know one way, so this is what i will show you

> 1. Pres ```sel``` of the ```mix-bus``` you want to send
> 2. Pres ```Fader Flip```
> 3. Turn fader up on the ```Matrix``` bus you want to use.

## Mixing/Mastering

## Extended guide of recording.

