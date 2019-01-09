from pytube import YouTube 
url  = input('Please enter the video url: ') 
if url: 
    print('Download starting...') 
    try: 
        video = YouTube(url).streams.first().download(filename = "video")
        print('Download complete! :)')
    except:
        print('Download FAILED! :(')
else:
    print('Bruh, you didn\'t type anything in. :/')
