<h2 align="center"> 🎬 MOVIE DOWNLOADER 🎬 </h2></br>
<div id="logo" align= "center">
            
<a href="https://sinhalasub.lk/">
<img src="https://sinhalasub.lk/wp-content/uploads/2023/08/icon.png" alt="SinhalaSub" height="60" width="120">
</a>
</div></br>

<a name = "links">
<p align = "center">This is Unofficial Web scraper of sinhalasub.lk web site.</p>
</br>
• <a href = "#install" alt = "">Install Npm Package</a></br>
• <a href = "#require" alt = "">Require Npm Package</a></br>
• <a href = "#start" alt = "">Getting Start</a>
</br>

### Using This npm 🚀

•  [Search Movies](#search)</br>
•  [Get New Updated Movies](#movies)</br>
•  [Get New Updated TvShows](#tvshows)</br>
•  [Get Episodes Using TvShow Link](#episodes)</br>
•  [Download Movies and Tv Shows](#download)</br>

</br>

</a>
<a name = "install">
<h4><u>⬇️ Install Package.</u></h4>

```
npm install mrnima-moviedl
```
or
```
yarn add mrnima-moviedl
```
</br>
</a>
<a name = "require">
<h4><u>🚀 Require Package.</u></h4>

```
const { sinhalaSub } = require("mrnima-moviedl")
```
</br>
</a>
<a name = "start">
<h4><u>👾 Getting Start.</u></h4>

```
var movie = await sinhalaSub();
```
</br></a>
</br>
<a name = "search">
<h4>🔍 Search Movies and Tv Shows.</h4>

```
var name = "O2";
var result = await movie.search(name);
console.log(result)
```
<h5>✅ Result</h5>

```
{
  "creator": "MR NIMA",
  "status": true,
  "result": [
    {
      "title": "O2 (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/n9rH9of4930TAHgpQXlrENuAFU5-150x150.jpg",
      "link": "https://sinhalasub.lk/movies/o2-2024-sinhala-subtitles/",
      "type": "Movie"
    },
    {
      "title": "O2 (2022) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2022/06/7vYTXYsAICtANvrUHNkLG1M6NKP-150x150.jpg",
      "link": "https://sinhalasub.lk/movies/o2-2022-sinhala-subtitles/",
      "type": "Movie"
    },
    {
      "title": "Japan (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/11/5Z8hNvpenAJJrtTFONoytov7zW9-150x150.jpg",
      "link": "https://sinhalasub.lk/movies/japan-2023-sinhala-subtitles/",
      "type": "Movie"
    },
    {
      "title": "Gen V (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/10/uuot1N5AgZ7xRCKgm4ZCwOhgIJu-150x150.jpg",
      "link": "https://sinhalasub.lk/tvshows/gen-v-2023-sinhala-subtitles/",
      "type": "TV"
    },
    {
      "title": "Kabir Singh (2019) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/08/q2jY2IKv1hpnkgbAvILVupZMFyq-150x150.jpg",
      "link": "https://sinhalasub.lk/movies/kabir-singh-2019-sinhala-subtitles/",
      "type": "Movie"
    }
  ]
}
```
</a>
</br>
<a name = "movies">
  <h4>🎬 New added Movies List</h4>
  
```
var page = "1";
var result = await movie.newMovies(page);
console.log(result)
```
<br>
<h5>✅ Result</h5>

```
{
  "creator": "MR NIMA",
  "status": true,
  "result": [
    {
      "title": "O2 (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/n9rH9of4930TAHgpQXlrENuAFU5-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/o2-2024-sinhala-subtitles/",
      "date": "Apr. 19, 2024"
    },
    {
      "title": "The Best Man (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/c9f6mFZqkyz4AD0sxGmynE1pe0v-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/the-best-man-2023-sinhala-subtitles/",
      "date": "Apr. 21, 2023"
    },
    {
      "title": "House of Lies (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/sCkwIC1al8FukrrRYFQOk2fxmHZ-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/house-of-lies-2024-sinhala-subtitles/",
      "date": "May. 31, 2024"
    },
    {
      "title": "White Rose (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/y72DvP0CbSEH753exvasEFgMB3K-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/white-rose-2024-sinhala-subtitles/",
      "date": "Apr. 05, 2024"
    },
    {
      "title": "District C-11 (2017) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/l9SxBVzrieUbBKr1lhaJ8StF2wD-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/district-c-11-2017-sinhala-subtitles/",
      "date": "Mar. 21, 2017"
    },
    {
      "title": "Hot Spot (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/pPIFfv9XVx2LEll9SxHAm8wvn7e-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/hot-spot-2024-sinhala-subtitles/",
      "date": "Mar. 29, 2024"
    },
    {
      "title": "Bagh Bandi Khela (2018) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/06/x6NXLTJQp7TJM9EaXIpbpoRfqxu-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/bagh-bandi-khela-2018-sinhala-subtitles/",
      "date": "Nov. 16, 2018"
    },
    {
      "title": "Theeviram (2020) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2020/12/fEnKFXzXeu1FQgbF5YFIgViVrgV-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/theeviram-2020-sinhala-subtitles/",
      "date": "Nov. 26, 2020"
    },
    {
      "title": "Poikkal Kuthirai (2022) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2022/09/x6JHobmxxwJ1ML2eMT0vpj4wrNf-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/poikkal-kuthirai-2022-sinhala-subtitles/",
      "date": "Aug. 05, 2022"
    },
    {
      "title": "Blink (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/xTUg83QvVKbG1Uud4lBD5SeuaNl-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/blink-2024-sinhala-subtitles/",
      "date": "Mar. 08, 2024"
    },
    {
      "title": "Stopmotion (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/kWzWZEctPcZ0dATbtcYy6lIJgGj-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/stopmotion-2024-sinhala-subtitles-%e0%b7%83%e0%b7%92%e0%b6%82%e0%b7%84%e0%b6%bd-%e0%b6%8b%e0%b6%b4%e0%b7%83%e0%b7%92%e0%b6%bb%e0%b7%83%e0%b7%92-%e0%b7%83%e0%b6%b8%e0%b6%9f/",
      "date": "Feb. 22, 2024"
    },
    {
      "title": "Atlas (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/bcM2Tl5HlsvPBnL8DKP9Ie6vU4r-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/atlas-2024-sinhala-subtitles/",
      "date": "May. 23, 2024"
    },
    {
      "title": "Irish Wish (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/v4Bb70dpIIQoEnZAHnm3nzCPauU-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/irish-wish-2024-sinhala-subtitles/",
      "date": "Mar. 14, 2024"
    },
    {
      "title": "Dhak Dhak (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/l3VtG2LeHL0AGnDC8dsDwmPu5PK-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/dhak-dhak-2023-sinhala-subtitles/",
      "date": "Oct. 13, 2023"
    },
    {
      "title": "Crew (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/03/8mnCtQngfhYt0W0BmkrCePutmvy-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/crew-2024-sinhala-subtitles/",
      "date": "Mar. 29, 2024"
    },
    {
      "title": "Tarot (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/gAEUXC37vl1SnM7PXsHTF23I2vq-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/tarot-2024-sinhala-subtitles/",
      "date": "May. 01, 2024"
    },
    {
      "title": "Ganapath (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/z5kngie7G0bR9CL3tcWhZLwIpIc-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/ganapath-2023-sinhala-subtitles/",
      "date": "Oct. 20, 2023"
    },
    {
      "title": "Kaliyugam Pattanamlo (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/05/6zQgg7epZg1JX72ok85LOPwIC6s-185x278.jpg",
      "link": "https://sinhalasub.lk/movies/kaliyugam-pattanamlo-2024-sinhala-subtitles/",
      "date": "Mar. 29, 2024"
    }
  ]
}
```
</a>
</br>
<a name = "tvshows">
  <h4>🎥 New add Tv shows.</h4>
  
  ```
var page = "1";
var result = await movie.tvShows(page);
console.log(result)
```

<h5>✅ Result.</h5>

```
{
  "creator": "MR NIMA",
  "status": true,
  "result": [
    {
      "title": "House of Ninjas (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/02/AoEuSoSnwSSnX1YzykDdOiKAZNB-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/house-of-ninjas-2024-sinhala-subtitles/",
      "date": "Feb. 15, 2024"
    },
    {
      "title": "Killer Soup (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/01/jm08lHmvZulDzxd5koPs8pf8Mir-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/killer-soup-2024-sinhala-subtitles/",
      "date": "Jan. 11, 2024"
    },
    {
      "title": "Percy Jackson and the Olympians (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/12/upmXGc1QovmPBU0mQJR2re6ruKd-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/percy-jackson-and-the-olympians-2023-sinhala-subtitles/",
      "date": "Dec. 19, 2023"
    },
    {
      "title": "Echo (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/01/vFyJH630cF68LohVYjQW49074Sy-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/echo-2024-sinhala-subtitles/",
      "date": "Jan. 09, 2024"
    },
    {
      "title": "Aakhri Sach (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/01/wuaP3whkA234QZ18JFhA9Q5oWgi-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/aakhri-sach-2023-sinhala-subtitles/",
      "date": "Aug. 25, 2023"
    },
    {
      "title": "Berlin (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/01/69YuvoiWTtK6oyYH2Jl4Q6SgZ59-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/berlin-2023-sinhala-subtitle/",
      "date": "Dec. 29, 2023"
    },
    {
      "title": "Shaitan (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2024/01/ujA4ZWKrtMlbpzP6r2FVeoUl65h-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/shaitan-2023-sinhala-subtitles/",
      "date": "Jun. 15, 2023"
    },
    {
      "title": "The Village (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/12/The-Village-2023-poster-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/the-village-2023-sinhala-subtitles/",
      "date": "Nov. 24, 2023"
    },
    {
      "title": "Vigilante (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/11/lauvBkCZhcZHj5uUwUxwr5GTPps-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/vigilante-2023-sinhala-subtitles/",
      "date": "Nov. 08, 2023"
    },
    {
      "title": "Dhootha (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/12/jMegWqCj8z58na8RG8ytlPJ7gGm-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/dhootha-2023-sinhala-subtitles/",
      "date": "Nov. 30, 2023"
    },
    {
      "title": "A Good Day to be a Dog (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/10/yzrgREOGseOgCtPbfoE3uW9Xuvq-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/a-good-day-to-be-a-dog-2023-sinhala-subtitles/",
      "date": "Oct. 11, 2023"
    },
    {
      "title": "Hwarang: The Poet Warrior Youth (2016) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2021/06/sXEiMRfG2IiSpa7gVWY401L6n21-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/hwarang-the-poet-warrior-youth-2016-sinhala-subtitles/",
      "date": "Dec. 19, 2016"
    },
    {
      "title": "Loki (2021) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2021/07/kEl2t3OhXc3Zb9FBh1AuYzRTgZp-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/loki-2021-sinhala-subtitles/",
      "date": "Jun. 09, 2021"
    },
    {
      "title": "Song of the Bandits (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/11/4lls2JCt9g1YiusX3xLVSdSZ6cO-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/song-of-the-bandits-2023-sinhala-subtitles/",
      "date": "Sep. 22, 2023"
    },
    {
      "title": "Castaway Diva (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/11/csOKLKbiizE0mySOcim2gUugNHt-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/castaway-diva-2023-sinhala-subtitles/",
      "date": "Oct. 28, 2023"
    },
    {
      "title": "Adult Trainee (2021) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/11/myIFGCAPV2NPdbrdASJCx3hwUQQ-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/adult-trainee-2021-sinhala-subtitles/",
      "date": "Nov. 12, 2021"
    },
    {
      "title": "Prehistoric Planet (2022) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/10/yMdFsHKp4YX2CUkAQcZswxXDuoe-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/prehistoric-planet-2022-sinhala-subtitles/",
      "date": "May. 23, 2022"
    },
    {
      "title": "Doona! (2023) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
      "img": "https://sinhalasub.lk/wp-content/uploads/2023/10/eOCZIaGSUZzCAiz70G7kEQzuC0U-185x278.jpg",
      "link": "https://sinhalasub.lk/tvshows/doona-2023-sinhala-subtitles/",
      "date": "Oct. 20, 2023"
    }
  ]
}
```
</a>
</br>
<a name = "episodes">
  <h4>🔢 Get Episodes Links.</h4>

```
var tvShowLink = "https://sinhalasub.lk/tvshows/killer-soup-2024-sinhala-subtitles/";
var result = await movie.episodes(tvShowLink);
console.log(result)
```
<h5>✅ Result</h5>

```
{
  "creator": "MR NIMA",
  "status": true,
  "result": {
    "title": "Killer Soup (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
    "image": "https://sinhalasub.lk/wp-content/uploads/2024/01/jm08lHmvZulDzxd5koPs8pf8Mir-200x300.jpg",
    "date": "Jan. 11, 2024",
    "TMDB": "6.8",
    "first_air": "Jan. 11, 2024",
    "last_air": "Jan. 11, 2024",
    "seasons_count": "1",
    "episodes_count": "8",
    "creator": {
      "name": "Abhishek Chaubey",
      "link": "https://sinhalasub.lk/creator/abhishek-chaubey/"
    },
    "cast": [
      {
        "name": "Konkona Sen Sharma",
        "link": "https://sinhalasub.lk/cast/konkona-sen-sharma/",
        "caracter": "Swathi Shetty"
      },
      {
        "name": "Manoj Bajpayee",
        "link": "https://sinhalasub.lk/cast/manoj-bajpayee/",
        "caracter": "Prabhakar \"Prabhu\" Shetty/Umesh Pillai/Umesh Shantaram Mahto"
      },
      {
        "name": "Nassar",
        "link": "https://sinhalasub.lk/cast/nassar/",
        "caracter": "Inspector Hassan F."
      },
      {
        "name": "Sayaji Shinde",
        "link": "https://sinhalasub.lk/cast/sayaji-shinde/",
        "caracter": "Arvind Shetty"
      },
      {
        "name": "Anula Navlekar",
        "link": "https://sinhalasub.lk/cast/anula-navlekar/",
        "caracter": "Apeksha \"Appu\" Shetty"
      },
      {
        "name": "Lal",
        "link": "https://sinhalasub.lk/cast/lal/",
        "caracter": "Lucas Charles"
      },
      {
        "name": "Vaishali Bisht",
        "link": "https://sinhalasub.lk/cast/vaishali-bisht/",
        "caracter": "Khansama"
      },
      {
        "name": "Kani Kasruti",
        "link": "https://sinhalasub.lk/cast/kani-kasruti/",
        "caracter": "Kirthima Kadathanathan"
      },
      {
        "name": "Shilpa Mudbi",
        "link": "https://sinhalasub.lk/cast/shilpa-mudbi/",
        "caracter": "Asha Ritu"
      }
    ],
    "episodes_links": [
      [
        {
          "title": "Episode 1",
          "date": "Jan. 11, 2024",
          "link": "https://sinhalasub.lk/episodes/killer-soup-s1e1/"
        },
        {
          "title": "Episode 2",
          "date": "Jan. 11, 2024",
          "link": "https://sinhalasub.lk/episodes/killer-soup-s1e2/"
        },
        {
          "title": "Episode 3",
          "date": "Jan. 11, 2024",
          "link": "https://sinhalasub.lk/episodes/killer-soup-s1e3/"
        },
        {
          "title": "Episode 4",
          "date": "Jan. 11, 2024",
          "link": "https://sinhalasub.lk/episodes/killer-soup-s1e4/"
        }
      ]
    ]
  }
}
```
</a>
</br>
<a name = "download">
<h4>⬇️ Downlaod Movies and Episodes.</h4>

```
var link = "https://sinhalasub.lk/movies/o2-2024-sinhala-subtitles/"; // Put here to movie link or episode link
var result = await movie.download(link);
console.log(result)
```
<h5>✅ Result </h5>

```
//Download Movie
{
  "creator": "MR NIMA",
  "status": true,
  "result": {
    "title": "O2 (2024) Sinhala Subtitles | සිංහල උපසිරසි සමඟ",
    "image": "https://sinhalasub.lk/wp-content/uploads/2024/06/n9rH9of4930TAHgpQXlrENuAFU5-200x300.jpg",
    "date": "Apr. 19, 2024",
    "country": "India",
    "duration": "105 Min.",
    "genres": [
      "Science Fiction",
      "Thriller"
    ],
    "IMDB": "8.7",
    "TMDB": "",
    "director": {
      "name": "Raaghav Nayak",
      "link": "https://sinhalasub.lk/director/raaghav-nayak/"
    },
    "cast": [
      {
        "name": "Ashika Ranganath",
        "link": "https://sinhalasub.lk/cast/ashika-ranganath/",
        "caracter": "Shraddha"
      },
      {
        "name": "Praveen Tej",
        "link": "https://sinhalasub.lk/cast/praveen-tej/",
        "caracter": "Dev"
      },
      {
        "name": "Raaghav Nayak",
        "link": "https://sinhalasub.lk/cast/raaghav-nayak/",
        "caracter": "Osho"
      },
      {
        "name": "Prakash Belawadi",
        "link": "https://sinhalasub.lk/cast/prakash-belawadi/",
        "caracter": "Dr. Mrutyunjay"
      },
      {
        "name": "Siri Ravikumar",
        "link": "https://sinhalasub.lk/cast/siri-ravikumar/",
        "caracter": "Shrushti"
      },
      {
        "name": "K.S. Sridhar",
        "link": "https://sinhalasub.lk/cast/k-s-sridhar/",
        "caracter": "Dr. Roy"
      },
      {
        "name": "Puneeth B A",
        "link": "https://sinhalasub.lk/cast/puneeth-b-a/",
        "caracter": "Venky"
      },
      {
        "name": "Gopalkrishna Deshpande",
        "link": "https://sinhalasub.lk/cast/gopalkrishna-deshpande/",
        "caracter": ""
      }
    ],
    "links": [
      {
        "quality": "FHD 1080p",
        "size": "2.68 GB",
        "link": "https://t.me/Sinhalasubnet_bot?start=Z2V0LTEwODA4NjI0OTM0NjY3OTY4"
      },
      {
        "quality": "HD 720p",
        "size": "1.32 GB",
        "link": "https://t.me/Sinhalasubnet_bot?start=Z2V0LTEwODA3NjIzMzk0MTgxMDY0"
      },
      {
        "quality": "SD 480p",
        "size": "683 MB",
        "link": "https://t.me/Sinhalasubnet_bot?start=Z2V0LTEwODA2NjIxODUzNjk0MTYw"
      },
      {
        "quality": "FHD 1080p",
        "size": "2.68 GB",
        "link": "https://mega.nz/file/UqlW2BaI#zlXQ4dUVUS-D2I6LKrIV3QhNy4sS7GDucmSBacK2sd0"
      },
      {
        "quality": "HD 720p",
        "size": "1.32 GB",
        "link": "https://mega.nz/file/wyd1QAKa#JSjL6TOvocSo7VDaxXORp__hKaDzjC86j4P0-s4HuWY"
      },
      {
        "quality": "SD 480p",
        "size": "683 MB",
        "link": "https://mega.nz/file/9ndn0ZaB#bjohexu01DtOAxFg22moIBjF76ZstVqQCKlqwhTP_OA"
      },
      {
        "quality": "FHD 1080p",
        "size": "2.68 GB",
        "link": "https://ddl.sinhalasub.net/4993/O2+%282024%29+Kannada+WEB-DL+-+1080p.mp4?hash=AgAD3x"
      },
      {
        "quality": "HD 720p",
        "size": "1.32 GB",
        "link": "https://ddl.sinhalasub.net/4991/O2+%282024%29+Kannada+WEB-DL+-+720p.mp4?hash=AgADXR"
      },
      {
        "quality": "SD 480p",
        "size": "683 MB",
        "link": "https://ddl.sinhalasub.net/4989/O2+%282024%29+Kannada+WEB-DL+-+480p.mp4?hash=AgADXB"
      }
    ],
    "direct_links": [
      {
        "quality": "FHD 1080p",
        "size": "2.68 GB",
        "link": "https://ddl.sinhalasub.net/4993/O2+%282024%29+Kannada+WEB-DL+-+1080p.mp4?hash=AgAD3x"
      },
      {
        "quality": "HD 720p",
        "size": "1.32 GB",
        "link": "https://ddl.sinhalasub.net/4991/O2+%282024%29+Kannada+WEB-DL+-+720p.mp4?hash=AgADXR"
      },
      {
        "quality": "SD 480p",
        "size": "683 MB",
        "link": "https://ddl.sinhalasub.net/4989/O2+%282024%29+Kannada+WEB-DL+-+480p.mp4?hash=AgADXB"
      }
    ]
  }
}

// Download Episode 
{
  "creator": "MR NIMA",
  "status": true,
  "result": {
    "title": "Vikings (2013) Sinhala Subtitles | සිංහල උපසිරසි සමඟ: 6x20",
    "episode_name": "The Last Act",
    "date": "Dec. 30, 2020",
    "links": [
      {
        "quality": "HD 720p",
        "size": "419.34 MB",
        "link": "https://001.sinhalasub01.workers.dev/0:/TV/Vikings%20(2013)/Season%2006/Vikings.720p.S06E20.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "419.34 MB",
        "link": "https://002.sinhalasub01.workers.dev/0:/TV/Vikings%20(2013)/Season%2006/Vikings.720p.S06E20.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "419.34 MB",
        "link": "https://003.sinhalasub01.workers.dev/0:/TV/Vikings%20(2013)/Season%2006/Vikings.720p.S06E20.mp4"
      },
      {
        "quality": "Subtitles",
        "size": "----",
        "link": "https://www.baiscope.lk/tv-series/vikings/"
      }
    ],
    "direct_links": [
      {
        "quality": "HD 720p",
        "size": "419.34 MB",
        "link": "https://001.sinhalasub01.workers.dev/0:/TV/Vikings%20(2013)/Season%2006/Vikings.720p.S06E20.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "419.34 MB",
        "link": "https://002.sinhalasub01.workers.dev/0:/TV/Vikings%20(2013)/Season%2006/Vikings.720p.S06E20.mp4"
      },
      {
        "quality": "HD 720p",
        "size": "419.34 MB",
        "link": "https://003.sinhalasub01.workers.dev/0:/TV/Vikings%20(2013)/Season%2006/Vikings.720p.S06E20.mp4"
      }
    ]
  }
}
```
</a>
</br></br></br>
<h6>
[ 🚀 Updates ]
</br>
 ⦁ Fix Episode Name ( title ) not Fetcher ( Downlaoder ).</br>
 ⦁ Add More details for getEpisode using tvShow link.</br>
 ⦁ Add date for new Movie and new tvShows.</br>
 ⦁ Add direct link filter ( can get only direct links, but some times not found ).

</h6>

[`⛼ GO UP`](#links)

## Author : [@mrnima](https://github.com/darkmakerofc)
###### email : mnimaofc@gmail.com

> MOVIE DOWNLOADER BY MR NIMA
