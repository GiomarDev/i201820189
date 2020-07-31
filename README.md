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
