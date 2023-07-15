# YRVSA_Dataset
YoutubeReviewVideoSentimentAnalysis (YRVSA) dataset is a collection of comments crawled from phone review videos on Youtube to make sentiment analysis towards the video or the product

## Introduction
As one of the most popular media, YouTube with its mass video sharing feature shapes an outlook of an object, as an example to be discussed in this research is  smartphones. YouTube facilitates users to respond to the video in several ways, one by leaving a comment on the video [11]. The contents of the word can have a more varied purpose and can be addressed to how the video is delivered or directed to the goods being reviewed, which is a smartphone. Comments can be more informative as netizens can give their opinions on a product or how to deliver the video. The following example is a comment on a smartphone review video that contains negative sentiment:

    "ngomongya ngaler ngidul,..sgala di bahas, udah fokus di hp aja ngebahasnya"

The comment is more focused on how the video is presented since there is a word ```ngomongnya``` that refers to the way the person in the video talk, and ```ngaler ngidul``` represent the way the reviewer talk was unfocused. 

Here's another example where the comment gives positive sentiment:
    
    "Hp ini kan gak cuma jual performa gan, disein cantik abis dan guna gak hanya gimmick"

The word ```disein cantik abis``` refers to the phone design which amazed the viewer. The word ```disein``` is actually slang for ```desain``` or ```design```, this illustrates the variety of slang by Indonesians. By analyzing sentiment and the type of comments, the focus of users' opinions can be identified as either a product and/or video [2]. For businesses, this is very influential because they get a rating from netizens on their products. Besides that, YouTubers can evaluate how their reviews are delivered in a video.

## About the Dataset
The dataset contains 13,638 Indonesian comments from 206 phone video reviews from YouTube. It was crawled in 2017, manually annotated by Ekki Rinaldi, then verified by Language Expert Dra. Lucia Sri Suharjanti.

The datasets has 8 classes:
| CLASS            | DESC                                                          | Example                                                                                                   | COUNT |
|------------------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|-------|
|     ```off-topic```    | the comment does not refer to the video or product            | PERTAMAX !                                                                                                |  2935 |
| ```product-negative``` | the comment refers to the product and gave negative sentiment | kenapa untuk ini kerpatan pixelnya tergolong biasa saja mungkin termasuk dibawah rata2                    |  537  |
|  ```product-neutral``` | the comment refers to the product and gave neutral sentiment  | ZenFone Max (ZC550KL) sama zenfone 2 ze550kl bagus mana ya ? secara keseluruhan                           |  2063 |
| ```product-positive``` | the comment refers to the product and gave positive sentiment | Iphone emang keren sob gak jual spek tp pas uji coba ampun dah emg harga gak bisa bohong..                |  301  |
|       ```spam```       | the comment contain link                                      | http://www.lazada.co.id/xiaomi-mi-iv-hybrid-dual-drivers- earphones-in-ear-headphones-silver-4671745.html |   34  |
|  ```video-negative```  | the comment refers to the video and gave negative sentiment   | endingnya kok kurang cetar gitu bang...                                                                   |  468  |
|   ```video-neutral```  | the comment refers to the video and gave neutral sentiment    | instrument background musicnya judulnya apa bang...??                                                     |   14  |
|  ```video-positive```  | the comment refers to the video and gave positive sentiment   | gw suka sma sobat hape. gokil smuah orgnya top banget dan ga garing                                       |  486  |

## Publication
[FVEC-SVM for opinion mining on Indonesian comments of youtube video](https://ieeexplore.ieee.org/document/8285860)https://ieeexplore.ieee.org/document/8285860
