<img src="https://media3.giphy.com/media/ln7z2eWriiQAllfVcn/200w.webp" width="100"><img src="https://i.giphy.com/media/LMt9638dO8dftAjtco/200.webp" width="100"><img src="https://i.giphy.com/media/eNAsjO55tPbgaor7ma/200w.webp" width="100"><img src="https://i.giphy.com/media/VgGthkhUvGgOit7Y9i/200.webp" width="100"><img src="https://media3.giphy.com/media/kdFc8fubgS31b8DsVu/giphy.webp" width="100"><img src="https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp" width="100"><img src="https://i.giphy.com/media/IdyAQJVN2kVPNUrojM/200.webp" width="100">

<img align="right" alt="GIF" height="300px" src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" />


class Gondar_Ra:
    def __init__(self):
        self.user_socials = []
    
    def socials(self, socials: list):
        for item in socials:
            if item == 'twitter':
                self.user_socials.append('twitter : GondarMC')

            elif item == 'discord':
                self.user_socials.append('discord : @Gondar Ra⚡#0505')

            elif item == 'twitch':
                self.user_socials.append('twitch : GondarRa')
                
            elif item == 'instagram':
                self.user_socials.append('twitch : gl_gondar')
                
            else:
                self.user_socials.append(f'{item} : unknown')
        return self.user_socials

    def bio(self):
        name      : str = "Giomar"
        age       : str = "19"
        birthday  : str = "09/01/2001"
        status    : list = ["student", "developer"]
        languages : list = ["spanish", "english"]
        return name, age, birthday, status, languages

if __name__ == "__main__":
    client = Gondar_Ra()
    socials = client.socials(['twitter', 'twitch', 'discord', 'instagram'])
    bio = client.bio()
    for i in socials:
        print(i)
    print(bio)
