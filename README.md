<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Classroom of the Elite Fandom</title>
  <style>
    
body {
  background-image: url('https://i.ytimg.com/sh/Yz5tD3QU7pLBAffNG9vE9g/market_sd.jpg');
  background-size: cover; /* or 'contain' depending on your preference */
  background-position: center;
  margin: 0;
  padding: 0;
  height: 94vh; /* Set to 100vh to cover the entire viewport */
  backdrop-filter: blur(2px);
}

    .container {
      background-color: rgb(255, 255, 255, 0.8);
    }

header{
  text-align: center;
  color: rgb(0, 0, 0);
  font-size: 40px;
  font-family: sans-serif;
  font-weight: bold;
  text-shadow: 4px 4px 8px #00ffff;
}
    
    h1 {
      color: rgb(0,155,155, 0.6);
      text-align: center;
      text-shadow: 3px 6px 8px #00ffff;
      font-size: 50px;
    }
    
    .Eps{
    background-color: rgb(255, 255, 255, 0.8);
    }
    
    .Ep{
     text-align: center;
    }
    .Ep button{
     border: none;
      background: none;
      color: #FF00FF;
      padding: 2px;
      cursor: pointer;
      margin: 5px;
    }
    
    .b {
      text-align: center;
    }

    .b button {
      border: none;
      background: none;
      color: orange;
      padding: 2px;
      cursor: pointer;
      margin: 5px;
    }

    /* Style for the image */
    #characterImage {
      display: block;
      margin: 0 auto;
      /* Centers the image */
      width: 200px;
      /* Adjust the width as needed */
      height: auto;
      /* Maintains aspect ratio */
      border-radius: 10px;
    }
  </style>
  <script>
    function displayInfo(character) {
      var paragraph = document.getElementById('Paragraph');
      var characterInfo = '';
      var imageUrl = ''; // Define imageUrl variable

      if (character === 'Ayonokoji') {
        characterInfo = 'Kiyotaka Ayanokōji (綾あやの小こう路じ 清きよ隆たか, Ayanokōji Kiyotaka) is the main protagonist of the You-Zitsu series. He is currently a second-year student of Advanced Nurturing High School. Following the entrance exam in which he scored precisely 50 points in every subject, he was placed in D-Class. In the anime adaptation, he sits at the rear left corner of the class seat next to Suzune Horikita.';
        imageUrl = 'https://i.pinimg.com/originals/4d/b0/71/4db0719744d73a1ad88e0f9fc1db649b.jpg';
      } else if (character === 'Horikita') {
        characterInfo = 'Suzune Horikita (堀ほり北きた 鈴すず音ね, Horikita Suzune) is one of the main characters of the You-Zitsu series and the main heroine of the √Horikita spin-off manga. She is known to be the younger sister of Manabu Horikita, the Student Council president of the school on the 1st Year Arc.';
        imageUrl = 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIK0adT7sVexbP_8kAveEYN2YUuSkFb3jdMA&usqp=CAU'; // Add Horikita's image URL
      } else if (character === 'Hirata') {
        characterInfo = 'Yōsuke Hirata (平ひら田た 洋よう介すけ, Hirata Yōsuke) is currently a second-year student of Advanced Nurturing High School. At the start of the series, he was introduced as the class representative and a student of Class 1-D, seated on the leftmost seat of the second row, next to Kei Karuizawa. He is considered as one of the top students in his class. He is also a member of the Soccer Club. His excellent grades are worthy of being in a more elite class; however, he ended up in Class D for reasons yet to be explained.';
        imageUrl = 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTnq24lA_MTB-PaTTg0WWzE4uDytYcEiO15dFD6QofdV3WIur-bJb78bog&s=10'; // Add Hirata's image URL
      } else if (character === 'Karuizawa') {
        characterInfo = 'Kei Karuizawa (軽かる井い沢ざわ 恵けい, Karuizawa Kei) is one of the heroines of the You-Zitsu series as well as a second-year student of Advanced Nurturing High School. She is a prominent figure in the class and is considered to be the girls leader of Class D.';
        imageUrl = 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRAWjhaReNd4cDg-JKsGWl4YJMB_6El9i39fQ&usqp=CAU';

      } else if (character === 'Sudou') {
        characterInfo = 'Ken Sudō (須す藤どう 健けん, Sudō Ken) is a student of class 2-D and a member of the Basketball Club. Due to his poor academic ability, he is referred to as one of the 3 Idiots of D-Class. Regardless of this, his athletic ability is without a doubt one of the best among the school.';
        imageUrl = 'https://i.pinimg.com/736x/b8/3d/8b/b83d8b364b9555fb41c588b1574608eb.jpg';
      
      } else if (character === 'Yamauchi') {
        characterInfo = 'Haruki Yamauchi (山やま内うち 春はる樹き, Yamauchi Haruki) is a former student of Class 1-D who is also known as one of the 3 Idiots of D-Class.';
        imageUrl = 'https://cdn.myanimelist.net/images/characters/12/492387.jpg';
      
      }  else if (character === 'Kushida') {
        characterInfo = 'Kikyō Kushida (櫛くし田だ 桔き梗きょう, Kushida Kikyō) is one of the main characters of the You-Zitsu series. She is a student of Class 1-D. She is quite popular in her class as well as the whole school as she aims to befriend everyone.';
        imageUrl = 'https://i.pinimg.com/736x/56/77/d6/5677d642f1f3ac8585f1fb7a07b093b5.jpg';
     
     } else if (character === 'Kōenji') { 
  characterInfo = 'Rokusuke Kōenji (高円こうえん寺じ 六助ろくすけ, Kōenji Rokusuke) is one of the students of Class 1-D who comes from a well-known family of scholars. However, he ended up in Class-D for his egotistical behavior.';
  imageUrl = 'https://i.pinimg.com/originals/76/22/df/7622dff6acf3849623037c6da6a53822.jpg'; 
  
    } else if (character === 'Sakura') {
        characterInfo = 'Airi Sakura (佐さ倉くら 愛あい里り, Sakura Airi) is a former student of Advanced Nurturing High School. She was previously in Class 1-D. She is also a former gravure idol with the stage name Shizuku (雫, Shizuku). In Second Year, Volume 5, she was expelled from school. After that she said she is going to continue her idol life and wanted to see her best friend when her best friend had graduated.';
        imageUrl = 'https://i.pinimg.com/originals/49/2a/09/492a09ebebdc5552620ddeb869bb00e3.jpg';
      } else if (character === 'Shinohara') {
      characterInfo = 'Satsuki Shinohara (篠しの原はら さつき, Shinohara Satsuki) is one of the students of Class 1-D.';
      imageUrl = 'https://preview.redd.it/satsuki-shinohara-v0-j63ftx71rdi91.jpg?auto=webp&s=2180a184f7726cba027a604c37e29788b4b81e82';
      
      } else if (character === 'Satō') {
      characterInfo = 'Maya Satō (佐さ藤とう 麻ま耶や, Satō Maya) is a student of Class 1-D.';
      imageUrl = 'https://i.pinimg.com/originals/5e/a7/b5/5ea7b50a3b029126fe4c487959bbcfca.png';
      
      } else if (character === 'Matsushita') {
      characterInfo = 'Chiaki Matsushita (松まつ下した 千ち秋あき, Matsushita Chiaki) is one of the students of Class 1-D.';
      imageUrl = 'https://i.pinimg.com/474x/e1/a6/48/e1a6488bf56c4417788e331093e7a009.jpg';
      
      } else if (character === 'Yukimura') {
      characterInfo = 'Teruhiko Yukimura (幸ゆき村むら 輝てる彦ひこ, Yukimura Teruhiko), also known as Keisei Yukimura (幸村 啓誠, Yukimura Keisei), is a student of Class 1-D. Despite his excellent academic ability, his poor athletic ability and his lack of social skills landed him in the D-Class. In the anime, he is seated in the first place of the fifth row, next to the door.';
      imageUrl = 'https://cdn.myanimelist.net/images/characters/14/456894.jpg';
      
      } else if (character === 'Miyamoto') {
      characterInfo = 'Sōshi Miyamoto (宮みや本もと 蒼そう士し, Miyamoto Sōshi) is a student of Class 1-D.';
      imageUrl = 'https://tiermaker.com/images/chart/chart/classroom-of-the-elite-all-characters--y2v7-577058/73--soshi-miyamotopng.png';
     
     }  else if (character === 'Inogashira') {
      characterInfo = 'Kokoro Inogashira (井いの頭がしら 心こころ, Inogashira Kokoro) is one of the students of Class 1-D.';
      imageUrl = 'https://i.pinimg.com/236x/6f/39/09/6f390956c819c74fd6136adc8dd858d0.jpg';
      
      } else if (character === 'Mori') {
      characterInfo = 'Nene Mori (森もり 寧々ねね, Mori Nene) is one of the students of Class 1-D.';
      imageUrl = 'https://i.redd.it/gadgmun1xtu51.jpg';
      
      } else if (character === 'Onodera') {
      characterInfo = 'Kayano Onodera (小野寺おのでら かや乃の, Onodera Kayano) is one of the students of Class 1-D. She is a member of the Swimming Club and is said to be the best swimmer out of the girls in her class.';
      imageUrl = 'https://cdn.myanimelist.net/images/characters/7/463430.jpg';
      // comment 
      } else if (character === 'Hondō') {
      characterInfo = 'Ryōtarō Hondō (本堂遼太郎, Hondō Ryōtarō) is one of the students of Class- 1-D. He is friends with Kanji Ike and Haruki Yamauchi from his class. He was one of the students who lost all their points in the first month at the Advanced Nurturing High School.';
      imageUrl = 'data:image/jpeg;base64,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';
      // comment
      
      } else if (character === 'Sotomura') {
      characterInfo = 'Hideo Sotomura (外そと村むら 秀ひで雄お, Sotomura Hideo) is one of the students of Class 1-D who is seated in the leftmost seat in the third row behind Yōsuke Hirata.';
      imageUrl = 'https://www.animeclick.it/immagini/personaggio/Hideo_Sotomura/cover/133659-Hideo_Sotomura-foto.jpg';
     
     } else if (character === 'Wang') {
      characterInfo = 'Mei-Yu Wang (王 美雨ワン・メイユイ, Wang Mei-Yui), nicknamed Mii-chan, is one of the students of Class 1-D.';
      imageUrl = 'https://i.pinimg.com/1200x/63/46/c4/6346c46fc550fb1ea193fce2cc655877.jpg';
      
      // comment2
      } else if (character === 'Miyake') {
      characterInfo = 'Akito Miyake (三み宅やけ 明あき人と, Miyake Akito) is one of the students of Class 1-D.';
      imageUrl = 'data:image/jpeg;base64,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';
      // comment2
     
     } else if (character === 'Hasebe') {
      characterInfo = 'Haruka Hasebe (長は谷せ部べ 波は瑠る加か, Hasebe Haruka) is one of the students of Class 1-D.';
      imageUrl = 'https://i.pinimg.com/736x/aa/29/7b/aa297b8ad6599bebb3629de6e94c0718.jpg';
      
      } else if (character === 'Okitani') {
      characterInfo = 'Kyōsuke Okitani (沖おき谷たに京きょう介すけ, Okitani Kyōsuke) is one of the students of Class 1-D. Even in Class D, he has particularly bad grades.';
      imageUrl = 'https://cdn.myanimelist.net/images/characters/2/440524.jpg';
     
     } else if (character === 'Ike') {
      characterInfo = 'Kanji Ike (池いけ 寛かん治じ, Ike Kanji) is one of the students of Class 1-D who is known as one of the 3 Idiots of D-Class. While his intelligence is poor, his communication skills are excellent.';
      imageUrl = 'https://i.pinimg.com/564x/e9/6b/1e/e96b1ed10713d277451c07d550c738a3.jpg';
      
      } else if (character === 'Ijūin') {
      characterInfo = 'Wataru Ijūin is a student of Class 1-D. He is the leader of the Ijūin Group, a clique of four boys who are loyal to him. He is known for his cheerful and friendly personality, as well as his gambling skills. He often helps out his classmates with various problems, sometimes for a price.';
  imageUrl = '';
      } 
    

      var imageContainer = document.getElementById('characterImageContainer');
      var characterImage = document.getElementById('characterImage');

      // If the content is already displayed, remove it; otherwise, display it
      if (paragraph.innerHTML === characterInfo) {
        paragraph.innerHTML = '';
        if (characterImage) {
          imageContainer.removeChild(characterImage);
        }
      } else {
        paragraph.innerHTML = characterInfo;
        if (imageUrl && !characterImage) {
          characterImage = document.createElement('img');
          characterImage.src = imageUrl;
          characterImage.id = 'characterImage';
          characterImage.classList.add('b');
          imageContainer.appendChild(characterImage);
        }
      }
    }
    
   

    function displayEpisodeInfo(episode) {
      var episodeInfo = '';
      var episodeName = '';

      // Define information for each episode
      if (episode === '1') {
        episodeName = 'Episode 1: What is Evil? Whatever Springs from Weakness.';
        episodeInfo = "Kiyotaka Ayanokōji joins the school in Class 1-D at the Tokyo Metropolitan Advanced Nurturing High School, an institution established by the government for training best students. Class-D's homeroom teacher, Sae Chabashira explains the point system as money, where everybody gets a monthly allowance of 100,000 points at local shops with one point equaling one yen. She warns the students that they are judged on merit. Kiyotaka navigates the system being careful about how he spends the points, while meeting the gregarious Kikyo Kushida and attempting to make peace with his selfish classmate Suzune Horikita. In an attempt to help Kushida become friends with Suzune, Kiyotaka brings them to a cafeteria, having secretly invited them and two other classmates. However, Suzune sees through the plan and leaves them. On April 30, the majority of Class-D lavishly spends their points and slacks off in class without reprimanding, making Kiyotaka suspicious. On May 1, the Class-D students are surprised to find out they did not get any allowance, and Chabashira explains that it depends on merit. After ignoring their studies, the class lacks points for a month.";
      } else if (episode === '2') {
        episodeName = "Episode 2: It Takes a Great Talent and Skill to Conceal One's Talent and Skill.";
        episodeInfo = "Chabashira explains how the system works at school. The four first-year classes are all ranked by merit, and Class-D has the opportunity to be promoted to Class-C with strong performances on exams. She warns that with the current situation, anybody who fails the exam will be expelled. Being aware of the system, everyone takes their studies often, except Ken Sudo, Kenji Ike and Haruki Yamauchi. Kiyotaka and Suzune discuss these matters, and she asks him to bring the boys aboard her study group in the library. Kiyotaka and Kushida fail to invite them, due to Suzune's selfishness. While Sudo lets everybody know he wants to play basketball, he has no interest in his studies. Kiyotaka discovers Suzune talking to her brother and Student Council President, Manabu. He threatens her over a disagreement about a misplaced view about independent isolation. Kiyotaka intervenes, and Manabu reveals that he scored fifty points on every test and asks if it was a coincidence or not. The midterm exams come, and Class-D as a whole performs very well with some points among the first years at school.";
      } else if (episode === '3') {
      episodeName = 'Episode 3: Man is an Animal that makes Bargains: No Other Animal Does This - No Dog exchanges Bones with Another.';
      episodeInfo = 'Class D gets the results of their last exam and everyone passes except for Sudo, who missed the passing threshold by one point. The grades were the result of Kiyotaka spending 15,000 points to buy exam questions from an upperclassman three days earlier. He explains that none of this is against school rules. Later, Kiyotaka discovers Chabashira asking her whether equality exists, and she answers that it does not and Kiyotaka agrees. Kiyotaka and Suzune spend their points to increase the test score by one point, so Sudo can stay in class. Kushida inadvertently leaves her cellphone, but Kiyotaka returns it to her. He ends up finding out about the jealous, nasty and irascible side of her personality. Kushida asks Kiyotaka to keep it a secret, or else she will accuse him of raping her.';
      
      } else if (episode === '4') {
      episodeName = 'Episode 4: We Should not be Upset that Others Hide the Truth from Us When We Hide it from Ourselves.';
      episodeInfo = "On July 1, Class-D's point distribution is put on hold, due to an incident the previous day involving Sudo and three basketball teammates from Class-C. Sudo was attacked and fought back in self-defense. However, due to poor reputation, he will be liable, unless the class can find a witness to clear his name before the hearing next week, which would consequently result in the class without points for the month. In an attempt to manipulate the case in their favor, the three Class-C attackers secretly request classmate Kakeru Ryuen to attack them. With the help of Class-B, the Class-D students post messages asking for witnesses of the incident. Suzune tells Kiyotaka and the others that Airi Sakura was there, and witnessed the incident with the camera. That night, Kiyotaka and Kushida discuss the truth, if one of the suspects is a killer, while the other is a law-abiding citizen, if there is a lack of evidence, people are more likely going to believe the law-abiding citizen even if they are guilty. The next day, Sakura is approached for the evidence, and she inadvertently drops the camera. She freaks out, when she cannot use it, thinking that she broke it and continues running, not wanting to get involved.";
      
      } else if (episode === '5') {
      episodeName = 'Episode 5: Hell is other People.';
      episodeInfo = "Sakura, Kiyotaka and Kushida inspect the camera covered under warranty at the electronics store. The store clerk asks Sakura about her contact information, but Kiyotaka uses his information instead. Kiyotaka figures out that Sakura is the internet model that became a big hit recently. At the hearing presided by Manabu, both classes give their testimonies accusing each other of instigating the fight with the initial ruling going in Class-C's favor. After staying silent, Suzune speaks up after Kiyotaka reminds her. Suzune asks what the circumstances were for the fight and points out that in a three against one fight, it is nearly impossible for injuries that serious to be all Sudo's doing. She presents Sakura as a witness providing evidence that she was present as she captured the fight going on in the background during a photoshoot. However, the evidence only proves that she was present and does not clear Sudo of any wrongdoing. The Class-C homeroom teacher Sakagami proposes a compromise to suspend Sudo for two weeks and the three Class-C students for one week each, but Class-D rejects it. Realizing that one side is clearly lying, Manabu ends the hearing, saying he will announce his decision the next day unless admissions or additional evidence is presented. He mentions that he can expel any students.";
      
      } else if (episode === '6') {
      episodeName = 'Episode 6: There are Two Kinds of Lies; One concerns an Accomplished Fact, the Other concerns a Future Duty.';
      episodeInfo = "Sakura returns to the dormitory and finds the photos in a mailbox. Taking advantage of the delay in the final ruling that was made possible with the photo, Kiyotaka and Suzune set up a trap at the stairwell. Kushida sends a fake message to three Class-C students, ordering them to meet her at the special annex in order to draw them to the stairwell, where Kiyotaka and Suzune are waiting, and Honami Ichinose installed security cameras. This helps them trick the Class-C students into believing neither side stands to gain by going forward with this complaint, and that the trio stands to get expelled because they told a malicious lie that got the school involved. As a result, the Class-C students agree to withdraw the complaint. Afterwards, the electronics store clerk and a big fan of the net alter ego Shizuku attacks Sakura, but Kiyotaka and Ichinose arrive to save her using the tracking feature in their phones and the security cameras to arrest the clerk. Chabashira mentions to Suzune that Class-D is a place for defectives in the school, and that Kiyotaka is one of them in her opinion. Manabu convinces Kiyotaka to join the student council, but he refuses while deferring the credit for settling the case to Suzune. Kiyotaka and Suzune plan to help the others reach Class-A.";
      
      } else if (episode === '7') {
      episodeName = 'Episode 7: Nothing is as Dangerous as an Ignorant Friend; A Wise Enemy is to be Preferred.';
      episodeInfo = "While studying at the dormitory room for summer vacation, Suzune is invited to the pool by Kiyotaka. Last night, a group of Class-D students, consisting of Kiyotaka, Sudo, Ike, Yamauchi and operation leader Hideo Sotomura, meet up to discuss preparations for peeping on the girls inside the changing room. During the trip, Sotomura observes the boys from the general storehouse, while communicating with transceivers and hand signals. With everyone invited, Yamauchi sneaks into the women's changing room as a janitor to secretly install the cameras under the pretense of closing it for cleaning. However, he has trouble doing it, and Ike enters there. Ryuen and students of Class-C approach the changing room, while Ike is still in. Needing help to escape, Sudo prevents Ryuen from entering the room, in order to stall for time, while students of Class-A arrive to start a fight. Manabu reminds everybody they are still being judged, as long as they are on school grounds. Sotomura informs Kiyotaka about the situation, and Suzune stands on the top of a diving platform to have a speech about Class-D ascending to Class-A someday. With the others distracted, Ike leaves the changing room unnoticed, and Suzune removes all SD cards from the cameras to foil the operation. Kiyotaka tells Suzune that he used her rather than other classmates, due to the possibility they would have done it behind his back.";
      
      } else if (episode === '8') {
      episodeName = 'Episode 8: Abandon All Hope, Ye Who enter Here.';
      episodeInfo = "For a class trip, all first-year students are taken on a luxurious cruise ship. Kiyotaka finds out from Chabashira that an unknown man had contacted the school asking for him to be expelled. Chabashira offers to cover for him in order for him to reach Class A. Suspecting that she may be manipulating him, he refuses, but she warns him that if he does, he will be expelled and stripped of his freedom. Later, Kiyotaka discusses with Suzune about the trip's destination. He tells her that he suspects the school is taking them to a boarding house on an island owned by the school for an ulterior motive. Ryuen tries to manipulate Suzune about the security camera set up. Another student from Class-C, Mio Ibuki, tries to confront Ryuen about something, but they are rebuffed by Albert. Suzune remarks that Class-C could be on the verge of collapsing from the inside. Sakayanagi plots in the background and investigates with other students. Later, Sakura asks Kiyotaka to go out on a date, but suddenly changes her mind when he goes to meet her. When Kushida sees them, Sakura is embarrassed and leaves. Kiyotaka tries to leave, but is stopped by Kushida, when she reverts to her anger personality. She tells him that she could sense his wariness of her, which he confirms. Kushida switches back to her cheerful personality and confesses that she feels lonely when left alone. The next day, the school informs all the students of the real reason behind the trip. They are required to take a survival test on a deserted island for a week.";
      
      } else if (episode === '9') {
      episodeName = 'Episode 9: Man is Condemned to be Free.';
      episodeInfo = "Yosuke Hirata explains from the manual how the survival test works. The class gets 300 test points to spend on food and other conveniences, and whatever remains at the end of the week can be exchanged for class points. The class loses test points for injuries, polluting the environment, missing roll calls and violence against any classes. While Class-D determines to tough it out, the girls feel the need to have a portable toilet, the argument aside, Class-D determines to save up points. The splits up looking for a camping spot, and Kiyotaka is paired Sakura and Rokusuke Koenji. Kiyotaka leaves Koenji, while he and Sakura look for a spot to secure, recalling what Chabashira said about possessing a spot, in that only the designated class leader can do it and each possession that lasts for eight hours gets the team one special test point that is only redeemable for class points. Also, by risking fifty test points, the class gets to guess whom the leader from another class is. While looking for a spot, Kiyotaka sees Kohei Katsuragi holding the leader card while talking with classmate Yahiko Totsuka. Class-D reconvenes and sets up camp at a spot by the river. Suzune is chosen to be the leader for being responsible and not standing out. While gathering firewood, Kiyotaka, Yamauchi and Sakura, find an injured Mio, and Kushida decides to give her some of the fruit his classmates found. The class plans a strategy for spending their points as they set a limit of 180 points to buy two meals a day, a toilet, a tent, and thirty for unforeseen situations. However, the class suffers a setback when Koenji withdraws, despite not feeling ill as he claims he is, costing thirty points from Class-D.";
      
      } else if (episode === '10') {
      episodeName = 'Episode 10: Every Man has in Himself the Most Dangerous Traitor of All.';
      episodeInfo = "Kiyotaka and Suzune go to reconnoiter the situation at other camps. Class-B's camp is set up near a waterfall and operates much like Class-D's camp but at a better location. Class-A's camp is in a cave that is heavily guarded. Suzune attempts to take a peak, but turns away, when Katsuragi summons his security force and warns her that her actions might start a war. Class-C's camp is on a beach where, under Ryuen's leadership, all points have already been spent and the class treats this test like a vacation. Ryuen did this knowing that they will not be penalized if they had spent all of their test points beforehand. Ryuen berates Mio for defying him. That night, someone has secretly broke into the girl's tent and stole the phone from Class D camp. On the fourth day, Class-D does more reconnaissance to find out who are the class leaders. Kiyotaka and Sakura meet Ichinose at Class-C's camp, and learn that everybody except Mio had withdrawn from the test. On the fifth day, Kei Karuizawa finds out that her underwear was stolen. Class-D conducts a bag search, but Yamauchi finds it in Ike's bag. Kiyotaka takes it, but the girls demand a pat-down. When the pat-down search is conducted, Hirata finds Kiyotaka, but reports that he could not find it. Later, he talks with him and decides to take the underwear knowing that his reputation would be damaged the least for being the culprit, because Karuizawa is his girlfriend.";
      
      } else if (episode === '11') {
      episodeName = 'Episode 11: What People Commonly call Fate is Mostly their Own Stupidity.';
      episodeInfo = "In response to the item theft incident, trust within Class-D erodes and the girls of Class-D decide to separate the boys and girls camps. Mio asks Kiyotaka about the opinion for the thief, and he trusts her while telling her that Sudo suspects her. That night, Kiyotaka and Suzune sit by a campfire, and he notices that she has been sick during the entire test. Suzune had been resting in her room during the cruise in order to recover from her illness and is determined to tough it out. The next day, Class-D gathers food in advance of a rainstorm. While fishing in the river, Kiyotaka asks Suzune to check the leader card, confirming whether it is real and that Katsuragi was holding. However, he is still unsure after seeing it. Yamauchi approaches Suzune and puts mud on her hair, prompting her to throw him to the ground. While Suzune removes the mud from her hair, someone has secretly stole the leader card and allowed Kiyotaka to know about it. Shortly afterwards, someone has set the survival test manual ablaze, leading to even more trust issues for Class-D. Suspecting that it was Mio's doing while she is from another class, Suzune fails to retrieve her key card from Mio without anyone witnessing the fight. Mio brings the card to a mysterious student.";
      
      } else if (episode === '12') {
      episodeName = 'Episode 12: Genius Lives Only One Story Above Madness.';
      episodeInfo = "Mio notifies Katsuragi through a ham radio that she has secured Suzune's card, as Class-A and Class-C are revealed to be working together. The injured Suzune is withdrawn from the test. On the final day, the students remove their camps and the classes guess the leaders, with Class-B opting not to make any guesses. At the assembly, Ryuen reveals that he secretly forged a pact with Katsuragi to transfer 200 test points to Class-A, in exchange for the card or the photo. Class-C quickly spent the remaining 100 points, and everyone except for Ryuen, Mio and Kaneda, the last of whom was assigned to spy on Class-B, withdrawn from the test. Class-C would guess the leaders: Yahiko Totsuka for Class-A, Chihiro Shiranami for Class-B and Suzune for Class-D. The results are revealed, and the winner is Class-D with 225 points, followed by Class-B with 140 points, Class-A with 120 points and Class-C with no points. The students return to the cruise ship, where Arisu Sakayanagi reveals that things went according to plan in making everybody mistrust Katsuragi to weaken his leverage over the class as her ally Hashimoto secretly outed Class-A's leader to Ryuen. Kiyotaka tells Suzune that he allowed Mio to steal the card, and Kiyotaka became the leader replacing Suzune, ensuring that Class-A and Class-C incorrectly guessed her. As for guessing the other ones, he reveals that he only saw the backside of Katsuragi's card and knowing how cautious he was, he deduced that Totsuka was Class-A's leader. He was aware that Ryuen had not withdrawn, leading him to guess him as Class-C's leader as he saw him with the same radio Mio used. Refusing to jeopardize Class-D's alliance with Class-B, Kiyotaka opted not to name Class-B's leader. Ryuen reveals that the main motivation for the alliance with Class-A was he would sign a contract to receive 20,000 points from each student of Class-A, every month until graduation. In a meeting with Chabashira, Kiyotaka finds out from her that the man who wanted him expelled was his father. Kiyotaka tells Chabashira that despite his father's attempts to remove him from school, he will continue to defy him. Having told Suzune that she needs allies, Kiyotaka tells Hirata that she was responsible for Class-D's victory, in order to have others put their trust in her. However, Kiyotaka wants nothing to do with Suzune or anyone in his class as he only sees them, and humans in general, as tools, and will continue to use and sacrifice others as long as he 'wins' in the end.";
      
      } else if (episode === 's1') {
      episodeName = '(Season 2 Episode: 1) Episode 13: Remember to Keep a Clear Head in Difficult Times.';
      episodeInfo = "Akane Tachibana reports the first year s first Special Test results to Manabu Horikita. Back on the cruise, Yosuke Hirata asks Kiyotaka to accompany him to lunch, but the latter refuses after mentioning Kei Karuizawa. The first years are informed of a second Special Test -- each student is to meet at a rendezvous point at a certain time. Including himself, Kiyotaka s rendezvous consists of Kei and classmates Hideo Sotomura and Teruhiko Yukimura; there, an instructor explains the Special Test. The students are split into eight groups of 14, with three students from Classes A and B and four from Classes C and D, and each group under the name of a planet. The test is three days long, and at 8:00 am on the first day, the school declares a member of the group a 'VIP,' and the group discusses who the VIP is twice a day. After 30 minutes of the final day, everyone but the VIP sends a guess to the school. There are four cases of the test. Case 1: if everyone but the VIP's classmates sends the correct answer, each student will receive 500,000 private points and the VIP an extra 500,000. Case 2: if at least one person -- excluding the VIP's classmates -- sends a wrong answer, the VIP receives 500,000 private points. The remaining two cases apply if the VIP is exposed before the end of the test. Case 3: if a student sends the correct answer, they will receive 500,000 private points, their class will earn 50 class points, and the testing period is over for the group. Additionally, if the VIP's classmate sends the correct answer, it will be deemed invalid, and the test will continue. Case 4: if a student sends a wrong answer, their class will lose 50 class points, the VIP will receive 500,000 private points, and their class will receive 50 class points, and the testing period is concluded. Additionally, if the VIP's classmate sends a wrong answer, it will be deemed invalid, and the test will continue. On the day of the exam, neither Kiyotaka nor Suzune are VIPs. They discuss the formalities of the test when Class-C's Kakeru Ryuen inquires Suzune if she is a VIP and if she managed the outcome of the first test; she denies both claims, and Ryuen threatens both her and Class-D. At the first discussion, Kiyotaka's Mars group does introductions. Afterwards, Class-B's Honami Ichinose suggests going for Case 1, and while everyone agrees, Koji Machida and his Class-A classmates abstain from all discussions. Machida explains that those will lead to a student identifying the VIP and betraying everyone else, thus resulting in Case 3. Honami rebuttals that Machida's approach ruins a student's chance for redemption and notes that Case 1 allows classes of an equal number of students to receive an extra 500,000 private points. After the discussion, Shiho Manabe and the Class-C girls from the Mars group approach Kei, claiming that she bullied one of their classmates--Rika, but Machida comes to her aid. During the second discussion, the group is at a deadlock, and Honami suggests just chatting and going with the flow for now. At the end of day 1, Kei breaks down for an unknown reason.";
      
      } else if (episode === 's2') {
      episodeName = '(Season 2 Episode: 2) Episode 14: There Are Two Main Human Sins from Which All the Others Derive: Impatience and Indolence.';
      episodeInfo = "Hirata receives information from someone that Kikyo Kushida is a VIP, which he tells to Yukimura and Kiyotaka. Rokusuke Koenji presumably discovers the true VIP, and as a result, the Jupiter group's test has been concluded. Suzune is upset that Koenji made a reckless move, and she and Kiyotaka decide to unite Class-D to get the most class points. To do that, they decide to use Kei as a primary player since she has a powerful presence amongst the Class-D girls. Still, Kiyotaka notes that Kei has been unusually passive compared to her normal arrogant attitude. Ryuen once again shows up and declares his intent to win the test. He convinced his classmates to give in their phones, so he'll receive the results; he left after proposing that Classes B, C, and D should unite to take down Class-A, which Suzune refused. Elsewhere, Kei is recovering from her breakdown and refers to herself as a 'parasite' as she is codependent on others. Kiyotaka and Kikyo find each other, and she leaves after abashedly hugging him. Chie Hoshinomiya, the Class-B teacher, asks Sae Chabashira, the Class-D teacher, how Kiyotaka became the leader as the Island test ended, to which Sae doesn't answer. Kiyotaka watches as Kei begs Hirata for protection from Shiho, to which he agrees but states that he and Kei aren't dating; she dumps him after he suggests that she should apologize to Shiho and her crew. Kiyotaka comes out and deduces Kei's real personality, and Hirata says that she agreed to be her boyfriend just for protection, given that she was severely bullied. Before the third discussion, Kei asks Kiyotaka if he's the VIP, saying no. After both discussions, the Mars group is still at a deadlock, but Kiyotaka and Yukimura notice that Shiho and her crew are eyeing down Kei. After the fourth discussion, the girls follow Kei, and the boys trail closely behind. Shiho and the girls confront Kei once again, and Kei implies she did bully Rika. Upon hearing that, the girls physically attack Kei and push her to tears, and while Yukimura tries to intervene, Kiyotaka stops him to continue observing the situation.";
      
      } else if (episode === 's3') {
      episodeName = '(Season 2 Episode: 3) Episode 15: The Greatest Souls Are Capable of the Greatest Vices as Well as of the Greatest Virtues.';
      episodeInfo = "Yukimura and Kiyotaka finally intervene in the situation, but Kei chides them. On the third day, the Venus group's test has concluded; thinking that Class-C is trying to exploit the test, Kiyotaka sends an email to Shiho. Kei is lured to a secluded part of the ship when Shiho and her girls, along with their classmate Rika, show up. Shiho infers that Kei was bullied before, confirmed when Kei had a panic attack. Shiho coerces Rika into relentlessly slapping Kei while Kiyotaka watches-- revealing that his email to Shiho was about Kei. After the girls leave, Kiyotaka approaches the crying Kei and berates her current self; Kei talks about the experience of abuse. Kiyotaka finds a wound on her chest; upon seeing that, he vows to protect her in exchange for working with him to unite Class-D to win the test. Afterwards, Kiyotaka goes to Sae to buy something with his points. Before the final discussion, Honami and Kiyotaka talk about reaching Class-A, despite being in different classes but affirms that it's possible to reach Class-A with 20,000,000 private points; Kiyotaka admits that he saw her allocated points from before. During the final discussion, Tetsuya Hamaguchi from Class-B proposes that everyone show their assignations to reach Case 1. Even with the risk of someone exposing the VIP first, everyone complies one by one until Yukimura hesitates to show the email, shocking everyone when he reveals that he's the VIP and implores everyone to protect his identity until the end of the test. Kiyotaka created a ploy by trading his and Yukimura's cellphones --meaning that Kiyotaka is the VIP, but Honami exposed it after calling the former's phone. Kei and Kiyotaka talk about the real ploy: after deducing that she's the VIP, he proposes that not only they'd switch phones but also SIM Cards-- which he went to Sae for, and Kiyotaka trades Kei's phone to Yukimura. Honami reveals that she knew about the plan but decided not to expose it due to their alliance with Class-D. Class-C wins the test; Ryuen shows up and explains a Class-D student sold that Kikyo was one of the VIPs, and he leaves after threatening Suzune and Class-D.";
      
      }else if (episode === 's4') {
      episodeName = '(Season 2 Episode: 4) Episode 16: The Material Has to Be Created.';
      episodeInfo = "The VIPs were chosen based on their name's position in the Hiragana scripture and the corresponding planet group of said VIP. Class-D talks about how Class-C is not fully united. The school will hold a 13-event Sports Festival with the theme of Team Red vs Team White -- Team Red consists of Classes A and D, and Team White consists of Classes B and C. The Sports Festival has several merits (the top three placements have a choice between 1,000 private points or bonuses on their written exam) and demerits (the bottom ten placements lose bonuses on their written exam), and classes can decide participants for the events. Kiyotaka and Suzune discuss that strict preparation separates the Sports Festival from the previous two special tests; Suzune wants to win by 'unfair methods, but Kiyotaka believes they can win by 'normal' methods. Later, the class decides on choosing participants through skill or volunteering; Suzune suggests that they should pair stronger and weaker students to win the events, at the risk of the weaker students losing out on merits. Kei disagrees with Suzune's proposal. Kei refutes that personal choice for events is better and notes that Suzune looks down on everyone and can't unite the class with that attitude; Kei asks for Kikyo's opinion, who says to combine both ideas, and the class agrees. Kei and a few students are against Suzune's view, then Suzune gains the class' ire by calling them incompetent. Hirata reconciles by getting the class' votes on whose idea, and the majority chose Suzune's. Later, Kei and Kiyotaka discuss how he ordered her to refute Suzune's idea and get Kikyo's opinion; Kiyotaka predicts that there'll be a traitor amongst Class-D, then stops after Kei demands more. The class extensively trains for the Festival. After witnessing Suzune argue with a student, Kiyotaka wonders why she can't compromise; she believes that weaker people are to match the stronger people's rhythm to win. After a three-legged race, he surmises that she ignores her allies. Kiyotaka proposes that he, Suzune, and Kikyo go surveilling Team White, believing that Kikyo sold out her VIP information.";
      
      } else if (episode === 's5') {
      episodeName = '(Season 2 Episode: 5) Episode 17: Every Failure Is a Step to Success.';
      episodeInfo = "Kiyotaka and Suzune speculate that Kikyo is betraying the class because she's receiving private points from other classes. The three of them go surveilling Team White, much to Kikyo's chagrin that Suzune's present; Suzune blatantly asks if Kikyo did sell her VIP information, to which Kikyo denies and asks to trust her. The Sports Festival begins. Ken Sudo motivates Class-D, while Arisu Sakayanagi of Class-A observes the Festival. When Koenji drops out, Sudo lowers the class morale. Team Red loses the 'Topple the Pole' event when Ryuen beats down Sudo; things get worse when Suzune gets injured after colliding with Class-C's Saki Kinoshita. After failing to convince Koenji to rejoin, Suzune wishes that she had Kikyo's natural charisma and admits she liked her at some point. Team White continues targeting Sudo and Suzune, continuing to lower the Class-D morale. Kei and Kiyotaka believe that the Class-D traitor leaked the participation list to Ryuen to target Sudo and Suzune. Kiyotaka continues that he never wanted the class to win the Festival and that doing nothing is best for now. Sudo is enraged at being targeted, so much so that he punches Hirata and then leaves, drastically lowering class morale. Kiyotaka tells Suzune to be useful to convince Sudo to rejoin and use him as her personal 'weapon,' just as she is for Kiyotaka. During a short break, Kei and Hirata ask Kiyotaka who the traitor to which he doesn't answer and bluffs that it was Suzune's idea to submit the leaked list. Kikyo takes Suzune to the medical office, where Ryuen is waiting. He believes that Suzune injured Saki on purpose and demands 1 million private points or he will tell the school of the incident; Suzune thinks it's a bluff, but Ryuen demands the points and for Suzune to submit to him, to which he'll wait for her answer at the end of the festival. After seeing her brother in the hallway, Suzune implores that she knows her incompetence and won't trouble him anymore. She affirms that she has one last thing to do for the festival.";
      
      } else if (episode === 's6') {
      episodeName = '(Season 2 Episode: 6) Episode 18: Adversity Is the First Path to Truth.';
      episodeInfo = "Suzune tries to convince Sudo to rejoin but ends up scolding him after he refuses to. Sudo admits that he joined the Festival for attention and to get back at those talking bad about him; Suzune affirms that he mustn't give up and keep fighting, or he'll be worthless and will await his return. Before the break ends, Kiyotaka confronts Kikyo about her being the traitor. She initially denies the accusation but poses a notion as to why Kiyotaka didn't change the list if he knew she leaked the participation list, which she deduces would've caused inter-class confusion. She finally reveals that she is the traitor for leaking the list and selling her VIP information to Ryuen for her desire to see Suzune and Kiyotaka expelled. Suzune tries to convince Sudo one more time, talking about how they are the same in seeking acknowledgment from others. She talks about how she has always been seeking acknowledgment from her brother, outcasting herself from others to reach it; after going through her experiences with Class-D, she realizes that she can't fight alone and needs allies, which Sudo gives in after being moved by her words. Sudo rejoins the Festival and apologizes for his actions earlier. Suzune and a male student drops out of the final event, so Kikyo and Kiyotaka step in for them. For the final event -- a relay race -- Manabu and Kiyotaka talk about the statuses and future of Class-D, and the latter indulges the former in a race to learn more about him. As soon as Kiyotaka receives his baton, the two laps all the runners and run at dead heat, leaving the school in awe. At the end of the festival, Class-D ends up coming in last but praises Kiyotaka for his performance. Suzune talks about how she has personally grown and affirms her belief in helping Class-D become strong, which shocks Kiyotaka. Suzune meets with Ryuen to give her answer with Kikyo present. Suzune confronts her about her being the traitor and remarks to drop the fake appearance; Kikyo obliges and then reveals her intention to expel Suzune by any means necessary and 'remove' those who know her true personality. Ryuen reveals that he had Kikyo give the participation list and instructed Saki to hurt Suzune and pretend to be seriously injured. Suzune has been recording for her protection, to which Ryuen has been for his innocence should the matter reach the student council. Ryuen then receives an email from an anonymous user, a recording of him instructing Saki to injure Suzune. He praises the 'mastermind' of Suzune and Class-D for anticipating everything, and then he backs off for now.";
      
      } else if (episode === 's7') {
      episodeName = '(Season 2 Episode: 7) Episode 19: To Doubt Everything or to Believe Everything Are Two Equally Convenient Solutions; Both Dispense with the Necessity of Reflection.';
      episodeInfo = "Manabu Horikita announces his resignation as the Student Council president. In his place will be Miyabi Nagumo from Class 2-A, who plans to change the school into a meritocracy. After the assembly, Kohei Katsuragi from 1-A advises Kiyotaka, Suzune, and Class-D to be wary of Ryuen. After he leaves, Maya Sato from 1-D bashfully asks Kiyotaka to exchange their numbers and implies she has a crush on him. Despite Class-D coming last for the Festival, none of the students were expelled, much to Ms. Chabashira's surprise and content. She then lets the class know about the next Special Test, which will serve as their final exam: Paper Shuffle. Two students will be paired up and must score above 60 points as a pair -- even if X student scores 0 and Y student scores 60 -- or both students will be expelled. The pairs will be determined through a mini-test, and there is a threshold for the total points from all subjects. Each class will make questions for the exam, which will be answered by one of the other three classes; the class that made the questions can request other classes to do the test, and there will be a lottery in the event of a double request. The requestee and the requestor will go head-to-head, and whichever class scores higher will steal 50 class points from the other. Cheating will result in immediate expulsion. Suzune and Kiyotaka suggest preparing the class for Paper Shuffle. Kei and Kiyotaka exchange emails about her witnessing Maya's confession; Kei, Hirata, and Sudo join Suzune and Kiyotaka to prep for the exam. Kikyo asks to join in, much to Kiyotaka's suspicion; he and Suzune plan to rejoin the others as they leave to prep, as she prepares to tell him about Kikyo's past. Suzune explains that she and Kikyo went to the same middle school. Sometime before graduation, an incident imploded a class and rumour had it that a single female student was the catalyst, whom Suzune believes is Kikyo. Kiyotaka suggests she gets Kikyo expelled, but Suzune believes she can make Kikyo an ally. Meanwhile, Ryuen threatens his class to flush out the spy assisting the 'mastermind' of Class-D, who is revealed to be Shiho Manabe. Ryuen hypothesizes that the mastermind is Kiyotaka or Yukimura, based on their witnesses to Shiho bullying Kei. Kiyotaka and Suzune rejoin the others to devise a plan to have some students purposefully flunk the mini-test so that the highest scorers get paired with the lowest scorers to create an average threshold. Later that night, Kei and Kiyotaka have a conversation about the circumstances of Maya asking him out, and then he vows to protect Kei no matter what. The next day, the class agreed to Suzune's plan for the mini-test; Kiyotaka gets paired with Maya for Paper Shuffle.";
      
      } else if (episode === 's8') {
      episodeName = '(Season 2 Episode: 8) Episode 20: "The Wound Is at Her Heart.';
      episodeInfo = "Kikyo reminisces her thoughts on the aftermath of the class implosion. Class-D will have study sessions for Paper Shuffle, with Kikyo and Suzune as overseers. Kikyo rushes out of class as she receives an email. Yukimura offers to oversee a pair for Paper Shuffle -- Akito Miyake and Haruka Hasebe -- noting that unity and cooperation are necessary to win; Suzune asks Kiyotaka to join Yukimura's group to track progress. At Yukimura's study session, the students encourage Kiyotaka to stop holding back -- given his performance at the Festival. Kiyotaka advises preparing for any dirty tricks the classes make for the exam, noting that the school might have a system to mediate questions. Later that same day, Kiyotaka relays that information to Suzune as the two discuss keeping an eye on Kikyo by inviting him to oversee Suzune's group. Kiyotaka receives an email from Ryuen asking who's the mastermind of Class-D. At Suzune's study session, the kids tease Maya and Kiyotaka; afterwards, Suzune meets with Kikyo alone. The two make a bet for the Math exam of Paper Shuffle: if Suzune scores higher, Kikyo will stop messing with her; otherwise, if Kikyo wins, Suzune will get expelled. To acknowledge it as a real bet, Suzune gets her brother to witness the agreement. After he leaves, Kikyo senses that Kiyotaka is on a call with Suzune and asks him to meet with her. At the meetup, Kikyo adds another condition that if she wins, Kiyotaka will get expelled, to which he agrees; by agreeing, he wants to know about Kikyo's past to see why she is the way she is and get the whole picture, to which Kikyo complies. As a child, Kikyo was praised for being a top achiever, so much so that she craved praise and attention, which eventually stopped. She then decided to become the nicest, friendliest, and most caring person, so that others could rely on her and gain everyone's trust. This eventually took a toll on her mentally, despite continuing to put up a front. To combat her distress, she created a personal blog wherein she gossiped about her classmates. On that fateful day, her classmates found her blog and shunned her; tired of keeping up a front, she revealed every dirty secret of all her classmates, which eventually turned the class against themselves and imploded. She implies that she knows truths about some Class-D students, vital enough to ruin them. Getting praised and knowing the dirty truths about people thrills her enough to think about taking drastic measures: a monster created from the desire for recognition. She finishes her tirade by reminding Kiyotaka and Suzune about the conditions of the bet.";
      
      } else if (episode === 's9') {
      episodeName = '(Season 2 Episode: 9) Episode 21: If You Make a Mistake and Do Not Correct It, This Is Called a Mistake.';
      episodeInfo = "Kikyo informs Ryuen of her bet with Kiyotaka and Suzune; in exchange for their expulsion, Kikyo will let Class-C win Paper Shuffle. Later, Ryuen intrudes on Kiyotaka's study session and vaguely asks about the email to fish out the Class-D mastermind. A Class-C student, Hiyori Shiina, notes that Kiyotaka and Yukimura have forgettable faces. Thus, she isn't sure if they are the mastermind. Feeling comfortable with the study group, Haruka decides to make a friend group where they share their names with Akito, Kiyotaka, and Yukimura -- who asks to be called Keisei; Airi joins the group as well, dubbed the 'Ayanokoji Group.' Later that night, Kiyotaka calls Kei to play an important part for Paper Shuffle, which she agrees to do so, then sends a birthday wish to him. The next day, Suzune tracks the progress of everyone's study group. Kikyo reminds them to try their hardest, which Kei badly received. She calls out Kikyo for trying to motivate everyone and then not caring when someone fails; Kei then splashes a drink on her but then apologizes for the incident by offering her uniform. Sometime later, Kikyo volunteers to submit the test questions and asks Ms. Chabashira to discard any other copies from Class-D; later, Kikyo gives the questions to Ryuen as per their deal. The test day comes. Hirata is happy that Kei is with Kiyotaka and would be even happier if they date. During the Math test, Kikyo is shocked to see the questions. After the test, Kikyo chides Ryuen for what happened, who lets her know that Suzune saw through it all. Suzune asked Ms. Chabashira to accept her and only her copy of the questions and discard anyone else's. Kikyo finds a cheat sheet on her uniform, meaning that Ryuen handed his class copy to the Class-D mastermind, betraying Kikyo. Much to her chagrin, Kikyo begrudgingly agrees to fulfill her side of the bet, but declares that she'll sabotage Kiyotaka next. Ryuen would either give Class-D his class copy or change Kikyo's questions, to which he chose the latter; angry that Kiyotaka used him, he targets Kei to fish out Kiyotaka.";
      
      } else if (episode === 's10') {
      episodeName = '(Season 2 Episode: 10) Episode 22: People, Often Deceived by An Illusive Good, Desire Their Own Ruin.';
      episodeInfo = "Every student passed Paper Shuffle. While witnessing Honami Ichinose and Arisu Sakayanagi hang out, the Ayanokoji group notes that everything about Honami is perfect, which they find unsettling; to take down Class-C, they decide to target Honami. A Class-C student follows Kei around. Later that night, Kei lets Kiyotaka know of the incident and also lets him know that a Class-A student was spying on their study sessions. The next day, many Class-D students are being provoked by Class-C; Suzune notes that Ryuen is doing this to exploit the mastermind and that he isn't buying into her being said mastermind. While returning Suzune's book to the library, Kiyotaka sees Hiyori from Class-C and the two talk about books they like despite being in rival classes. Afterwards, Kiyotaka is taken to a reception room where his father awaits, whom he hasn't seen in a year and a half. Mr. Ayanokoji begins by saying their butler committed suicide after getting fired for helping Kiyotaka apply for the school and escape his father. Kiyotaka left his family to search for his path and live independently, which his father disallowed; to take matters further, he wants Kiyotaka to sign the school withdrawal form and rejoin the White Room. Just then, Mr. Sakayanagi, the school's chairman and Arisu's father, chimes in that Kiyotaka was enrolled in the school on behalf of Mr. Sakayanagi's recommendation and that no one has the right to forcefully withdraw a student, upon which Mr. Ayanokoji backs off and allows Kiyotaka to stay for now. After the meeting, Kiyotaka chastises Ms. Chabashira for using him for her reasons to ascend to Class-A. Later that night, Kiyotaka apologizes to Kei for using her and that he'll stop his desire to climb Class-D to Class-A as he will leave that to Suzune and Hirata, and he caps off the conversation by saying that this will be their last time talking.";
      
      } else if (episode === 's11') {
      episodeName = '(Season 2 Episode: 11) Episode 23: People, Often Deceived by An Illusive Good, Desire Their Own Ruin.';
      episodeInfo = "Kei recounts the conversation from the night before. Ryuen intrudes on Class-D; Koenji leaves class, with Ryuen and his men giving chase, making Class-D concerned. In the courtyard, Koenji is confronted by many Class-C students as Ryuen starts instigating by breaking Koenji's property. Arisu and some Class-A arrive to witness the altercation. Koenji infers that Ryuen is seeking the Class-D mastermind and diffuses the situation by claiming that he has no interest in the inter-class war and will do whatever he wants. Ryuen subsides his aggravation, but Arisu gaslights him by teasing him, upon which, Ryuen goes to kick her, only for a Class-A student, Hashimoto, to defend her. As everyone leaves, Ryuen threatens Suzune and Class-D and declares his search for the mastermind is concluding. Ryuen reveals his plan to fish out the mastermind by using bait, the latter of which is shown to be Kei. Ryuen lures Kei to a construction site and then bounds her. He forces her to reveal the mastermind, or else he will expose her past bullying to destroy her friendships. Kei continues protecting Kiyotaka and persuades Ryuen to let her go because it shows his weakness in using others for his objective. Upon hearing that, Ryuen begins torturing her, but Kei keeps her composure, bluffing that there is no mastermind. Meanwhile, Kiyotaka agrees to go to karaoke with his friends. Ryuen continues the torture and then drags her to a light source.";
      
      } else if (episode === 's12') {
      episodeName = '(Season 2 Episode: 12) Episode 24: Force Without Wisdom Falls of Its Own Weight.';
      episodeInfo = "Ryuen continues torturing Kei, saying that the mastermind abandoned her. He claims that the mastermind set Kei up during the Special Test on the ship, when she was lured to a secluded part wherein Shiho and Rika bullied her; Kei nearly gave in to revealing Kiyotaka, but keeps her composure, upon which Ryuen threatened to expose her past bullying, to which she accepts if it means helping Kiyotaka. Realizing something's wrong, Kiyotaka bails on the karaoke plan and instead goes to Ms. Chabashira, asking her to stop Ryuen from harming Kei for Class-D to advance; she agrees after Kiyotaka enlisted the help of Manabu to 'eliminate' Ryuen in exchange for Suzune joining the student council. Kiyotaka arrives at the gymnasium to save Kei, revealing himself as the mastermind, much to everyone's surprise. Ryuen threatens to beat up Kiyotaka in the face of sheer violence and orders his underlings to do so. Kiyotaka dispatches Albert and Ishizaki, then proclaims that he was in control of the entire war, duping Ryuen into believing otherwise. Annoyed by his remarks, Mio attacks Kiyotaka, but he easily knocks her out. Ryuen and Kiyotaka engage in an all-out brawl as the two taunt each other as to who will win; Kiyotaka confidently proclaims that he won't lose, while Ryuen's whole philosophy lies on the concept that violence is true power. Kiyotaka retaliates that he's numb to pain. When gaining the upper hand, he violently beats Ryuen's face and claims he is emotionless and mundane, driving fear and confusion into Ryuen as he loses the fight. Kiyotaka goes to comfort a scared Kei and reassures her that he will come to save her no matter what as she cries in his arms.";
      
      } else if (episode === 's13') {
      episodeName = '(Season 2 Episode: 13) Episode 25: The Worst Enemy You Can Meet Will Always Be Yourself.';
      episodeInfo = "After losing to Kiyotaka, Ryuen rethinks his decisions, which Mio is displeased with, given that he became docile. Kei is shocked that her feelings for Kiyotaka have grown stronger. Maya tells Kei that she's confessing to Kiyotaka in two days, on Christmas day, much to the latter's confusion, given her feelings for him; her confusion is further proven after he calls about things to know about Maya later that night. The next day, Kiyotaka lets Suzune know that her brother wishes for her to join the student council and believes it will benefit her later. Later that same day, Kiyotaka and Ryuen meet and the two talk about how the former saved the latter by Class-D taking part in the responsibility for the gymnasium incident. Kiyotaka will continue to observe Class-D's process to ascension and reveals his prediction of Class-D reaching Class-C and then getting demoted due to his intention to expel Kikyo the following term. On Christmas day, Kiyotaka and Maya meet, with Kei and Hirata accompanying them as a double date. The four watch a movie and then go for lunch; after Kei and Hirata leave, Maya confesses to Kiyotaka, and he turns her down due to never having romantic feelings for anyone. A dejected Maya walks away as Kei witnesses the rejection and asks if he views everyone as tools for his benefit, to which he neither confirms nor denies it. Kei gives him a present, to which Kiyotaka reciprocates by giving her cold medicine; as the two head back, he calls her by her given name for the first time and ponders how she's a good pawn but whether he'll ever stop thinking of others as such. As Kei and Kiyotaka part, Arisu follows him and reveals that she knows him through the White Room and her intention to take him down, to which he asks if she can do so, thus declaring a potential war.";
      }
      // Add more episodes following a similar pattern

      var episodeContainer = document.getElementById('episodeInfoContainer');
      var episodeDiv = document.createElement('div');
      episodeDiv.classList.add('episode');

      // If the content is already displayed, remove it; otherwise, display it
      var existingEpisode = document.querySelector('.episode');
      if (existingEpisode) {
        existingEpisode.remove();
      } else {
        var episodeTitle = document.createElement('h2');
        episodeTitle.textContent = episodeName;

        var episodeParagraph = document.createElement('p');
        episodeParagraph.textContent = episodeInfo;

        episodeDiv.appendChild(episodeTitle);
        episodeDiv.appendChild(episodeParagraph);
        episodeContainer.appendChild(episodeDiv);
      }
    }
    
  </script>
</head>

<body>
  <h1>Classroom of the Elite Wiki</h1>
    <header>Characters:-</header>
  <div class="container">
    <div class="b">
      <button type="button" onclick="displayInfo('Ayonokoji')"> Ayanokōji Kiyotaka</button>
      
      <button type="button" onclick="displayInfo('Horikita')">Horikita Suzune </button>
      
      <button type="button" onclick="displayInfo('Hirata')">Hirata Yōsuke</button>
      
      <button type="button" onclick="displayInfo('Karuizawa')"> Karuizawa Kei</button>
      
      <button type="button" onclick="displayInfo('Sudou')">Sudō Ken</button>
       
       <button type="button" onclick="displayInfo('Kushida')">Kushida Kikyō</button>
      
      <button type="button" onclick="displayInfo('Yamauchi')">Yamauchi Haruki</button>
     
     <button type="button" onclick="displayInfo('Sakura')">Airi Sakura</button>
     
     <button type="button" onclick="displayInfo('Kōenji')">Rokusuke Kōenji</button>
      
      <button type="button" onclick="displayInfo('Satō')">Maya Satō</button>
     
     <button type="button" onclick="displayInfo('Matsushita')">Chiaki Matsushita</button>
     
     <button type="button" onclick="displayInfo('Yukimura')">Teruhiko Yukimura</button>
     
     <button type="button" onclick="displayInfo('Miyamoto')">Sōshi Miyamoto</button>
     
     <button type="button" onclick="displayInfo('Shinohara')">Satsuki Shinohara</button>
     
     <button type="button" onclick="displayInfo('Inogashira')">Kokoro Inogashira</button>
     
     <button type="button" onclick="displayInfo('Mori')">Nene Mori</button>
     
     <button type="button" onclick="displayInfo('Onodera')">Kayano Onodera</button>
     
     <button type="button" onclick="displayInfo('Hondō')">Ryōtarō Hondō</button>
     
     <button type="button" onclick="displayInfo('Sotomura')">Hideo Sotomura</button>
     
     <button type="button" onclick="displayInfo('Wang')">Mei-Yu Wang</button>
     
     <button type="button" onclick="displayInfo('Miyake')">Akito Miyake </button>
     
     <button type="button" onclick="displayInfo('Hasebe')">Haruka Hasebe</button>
     
     <button type="button" onclick="displayInfo('Okitani')">Kyōsuke Okitani </button>
     
     <button type="button" onclick="displayInfo('Ike')">Kanji Ike</button>
     
     <button type="button" onclick="displayInfo('Ijūin')">Wataru Ijūin</button>
    </div>
    <p id="Paragraph"></p>
    <!-- Container for the character image -->
    <div id="characterImageContainer"></div>
  </div>
 
  <header>Episodes</header>
  <div class="Eps">
  <div class="Ep">
   
     <button type="button" onclick="displayEpisodeInfo('1')">Episode 1</button>
     <button type="button" onclick="displayEpisodeInfo('2')">Episode 2</button>
     <button type="button" onclick="displayEpisodeInfo('3')">Episode 3</button>
     <button type="button" onclick="displayEpisodeInfo('4')">Episode 4</button>
     <button type="button" onclick="displayEpisodeInfo('5')">Episode 5</button>
     <button type="button" onclick="displayEpisodeInfo('6')">Episode 6</button>
     <button type="button" onclick="displayEpisodeInfo('7')">Episode 7</button>
     <button type="button" onclick="displayEpisodeInfo('8')">Episode 8</button>
     <button type="button" onclick="displayEpisodeInfo('9')">Episode 9</button>
    <button type="button" onclick="displayEpisodeInfo('10')">Episode 10</button>
    <button type="button" onclick="displayEpisodeInfo('11')">Episode 11</button>
    <button type="button" onclick="displayEpisodeInfo('12')">Episode 12</button>
    <button type="button" onclick="displayEpisodeInfo('s1')">Episode 13</button>
    <button type="button" onclick="displayEpisodeInfo('s2')">Episode 14</button>
    <button type="button" onclick="displayEpisodeInfo('s3')">Episode 15</button>
    <button type="button" onclick="displayEpisodeInfo('s4')">Episode 16</button>
    <button type="button" onclick="displayEpisodeInfo('s5')">Episode 17</button>
    <button type="button" onclick="displayEpisodeInfo('s6')">Episode 18</button>
    <button type="button" onclick="displayEpisodeInfo('s7')">Episode 19</button>
    <button type="button" onclick="displayEpisodeInfo('s8')">Episode 20</button>
    <button type="button" onclick="displayEpisodeInfo('s9')">Episode 21</button>
   <button type="button" onclick="displayEpisodeInfo('s10')">Episode 22</button>
   <button type="button" onclick="displayEpisodeInfo('s11')">Episode 23</button>
   <button type="button" onclick="displayEpisodeInfo('s12')">Episode 24</button>
   <button type="button" onclick="displayEpisodeInfo('s13')">Episode 25</button>
    <!-- Add more buttons for other episodes -->
  </div>

  <div id="episodeInfoContainer"></div>

  </div>
</body>
</html>
