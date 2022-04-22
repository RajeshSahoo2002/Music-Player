# Music-Player

import vlc
import time
print("Let's Hear Some Soothing Musics 🎶🎶 🎶🎶 😉:")
print('Songs That Are Available:\n 1.Khairiyat \n 2.Kina Chir \n 3.Lut Gaye \n 4.Naacho Naacho \n 5.Dil Galti Kar Baitha Hai \n 6.Believer')
order=input("Enter the Music By The User:")
if "Khairiyat" in order:
    sound_file = vlc.MediaPlayer("C:\\Users\\HP\OneDrive\\Desktop\\Khairiyat (Sad) - Chhichhore 128 Kbps.mp3")
    sound_file.play()
    time.sleep(80)
elif "Kina Chir" in order:
    sound_file=vlc.MediaPlayer("C:\\Users\\HP\OneDrive\\Desktop\\02 Kina Chir - The PropheC 320Kbps.mp3")
    sound_file.play()
    time.sleep(120)
elif "Lut Gaye" in order:
    sound_file=vlc.MediaPlayer("C:\\Users\\HP\\OneDrive\\Desktop\\Lut Gaye - Jubin Nautiyal.mp3")
    sound_file.play()
    time.sleep(100)
elif "Naacho Naacho" in order:
    sound_file=vlc.MediaPlayer("C:\\Users\\HP\\OneDrive\\Desktop\\Naacho Naacho - RRR.mp3")
    sound_file.play()
    time.sleep(60)
elif "Dil Galti Kar Baitha Hai" in order:
    sound_file=vlc.MediaPlayer("C:\\Users\\HP\\OneDrive\\Desktop\\Dil Galti Kar Baitha Hai - Jubin Nautiyal.mp3")
    sound_file.play()
    time.sleep(80)
elif "Believer" in order:
    sound_file=vlc.MediaPlayer("C:\\Users\\HP\\OneDrive\\Desktop\\Believer(PagalWorld).mp3")
    sound_file.play()
    time.sleep(35)
