# Make Subtitle With Force 
make subtitle form English subtitle to Chinese&amp;English subtitle used google Translate.

## What I have done?

1. Extract the subtitles's starting time and ending time, It's twice than the subtitle's rows

```
00:00:22,640 --> 00:00:24,980
A kokujin came to my door.
```


2. If it's more than one line in the subtitle block, it should be combine into one line because it belonging to same sentence. 

So we can translate it precisely.

```
00:02:19,090 --> 00:02:23,430
That is why
I accepted the films.
```


3. Some rows many be the same sentence, we should combine it.

```
101
00:08:18,040 --> 00:08:22,000
Once fully opened, the gateway
produces an extreme
```

```
102
00:08:22,040 --> 00:08:24,630
amount of magnetic energy.
```
https://github.com/JustYummy/subtitle-making-with-force/blob/master/Pic/pic3.png

4. Inside the bracket, it's some background music hint, we can remove it.

```
00:09:02,790 --> 00:09:05,920
(indistinct chatter,dog barking)
```


5. We also can remove music hint.

```
00:02:39,360 --> 00:02:43,910
♪ Edelweiss ♪
```


6. Remove the name before main dialogue.

```103
00:08:25,880 --> 00:08:28,460
TECHNICIAN:
Ready for activation.
```


7. Remove some symbols before the dialogue.

```
00:37:37,460 --> 00:37:41,170
-Do I need a drink.
```

## How to use?
Run the script on the CMD like this:
```
python3 scriptPath inputSubtitlePath
```

<img src="https://github.com/JustYummy/subtitle-making-with-force/blob/master/Pic/pic.png" width = "600" alt="pic" align=center />
Alfter that you will receive the file path. Of cause it in the same folder as the input file path.
<img src="https://github.com/JustYummy/subtitle-making-with-force/blob/master/Pic/pic2.png" width = "600" alt="pic2" align=center />
And the output file like this:

![pic3](https://github.com/JustYummy/subtitle-making-with-force/blob/master/Pic/versusPic3.png)

