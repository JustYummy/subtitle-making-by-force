# Making Subtitle With Force 
making subtitle form English subtitle to Chinese&amp;English subtitle used google Translate.

## What I have done?

1.提取时间，时间数是字幕行数的两倍

Extract the subtitles's starting time and ending time, It's twice than the subtitle's rows

```
00:00:22,640 --> 00:00:24,980
A kokujin came to my door.
```

2.两段是同一句话，组合成一句便于翻译

If it's more than one line in the subtitle block, it should be combine into one line because it belonging tosame sentence. 

So we can translate it precisely.

```
00:02:19,090 --> 00:02:23,430
That is why
I accepted the films.
```

3.开头小写的和一行字幕为同一句话 

Some rows many be the same sentence, we should combine it.

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

4.括号内提示的可删除

Inside the bracket, it's some background music hint, we can remove it.

```
00:09:02,790 --> 00:09:05,920
(indistinct chatter,dog barking)
```

5.音乐可删除

we also can remove music hint.

```
00:02:39,360 --> 00:02:43,910
♪ Edelweiss ♪
```

6.去除人名提示

Remove the name before main dialogue.

```103
00:08:25,880 --> 00:08:28,460
TECHNICIAN:
Ready for activation.
```

7.去除文本前符号

Remove some symbols before the dialogue.

```
00:37:37,460 --> 00:37:41,170
-Do I need a drink.
```

