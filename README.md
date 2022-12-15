- 👋 Hi, I’m @DewanSK
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
DewanSK/DewanSK is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import pytube
# link of the video to be downloaded
link = "https://www.youtube.com/XXXXXXXXXXX"

# object creation using YouTube which was imported in the beginning 
yt = pytube.YouTube(link) 
  
# streams = yt.streams.all() 

# downloading the video 
stream = yt.streams.first()
stream.download()
