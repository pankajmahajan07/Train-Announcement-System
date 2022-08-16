# Train-Announcement-System
It is an automated software which will generate the Railway Station Announcement by maintaining a database of required information in an excel sheet.
![R](https://user-images.githubusercontent.com/109011314/184954229-9eb69dff-6f1f-4a5c-bb37-117b15edfd33.png)
# Announcement Languages
- Hindi
# Development Environment
- Used Python Language with a bunch of its libraries like pyAudio, pydub, pandas, openpyxl and gTTS to generate announcement status of thousands of trains.
- Used pyAudio to play and record audio.
- Used pydub and pandas for audio manipulation.
- Used openpyxl to read excel(.xlsx) file.
- Used gTTS(Google Text-to-Speech) to translate text to speech.
# Process
- First of all record the announcement of any of the train from the railway station or download it from the internet.
- Then trim the recorded sound of the train number and name, source, route, destination, platform number on which train is arriving, and so on seperately.
- Maintain a database in excel sheet of various information regarding the train number and name, source, route, destination, platform number, etc.
- Read that excel file and convert all those text to speech according to the Hindi  and create seperate audio files.
- And then finally merge that generated text to speech audio files with the trimmed audio files according to our database and name that combined audio file as - Announcement_TrainNumber.
- At the last, delete all intermediate seperate audio files to free up the unnecessary space occupied.
# Conclusion
The principle point of developing this is to give voice based announcement which requires less time to create the announcement and that too in various languages. This project can reach out to any number of stations. It is more efficient and convenient than the normal announcement.



