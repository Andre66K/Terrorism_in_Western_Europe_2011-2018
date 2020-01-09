<h2 style="box-sizing: border-box; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif; font-weight: bold; line-height: 1; color: rgb(0, 0, 0); margin: 1.27em 0px 0px; font-size: 21.994px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255); text-decoration-style: initial; text-decoration-color: initial;">Terrorism in Western Europe (2011-2018)</h2>
<h2>Introduction</h2>
<p>This project is a data mining analysis that aims to make a comparison between jihadist terrorist attacks and non-jihadist terrorist attacks in Western Europe from January 1, 2011 to December 31, 2018. Jihadist attacks are defined as all the attacks perpetrated by an individual or a group inspired by the Salafist and jihadist propaganda and ideology, regardless of if they were officially affiliated with a terrorist group or they acted as “lone wolves”. The category of non-jihadist attacks comprises all the attacks perpetrated by individuals or groups motivated by any different kind of ideology, including nationalist, racial, separatist and non-Islamic religious motives. The analysis compares four main factors: the countries where the attacks took place, the modus operandi of the terrorists, their targets and number of fatalities. The Western Europe area does not include all the members of the European Union, since some of them are located in Eastern Europe, and it includes some countries that are not members of the Union, such as Switzerland and Norway. Moreover, this analysis does not take into consideration the terrorist plots disrupted by the authorities, but instead focuses exclusively on the attacks that actually took place, whether successful or not.</p>
<p>This research considers the data starting from 2011 because it is considered a transition year for jihadism in Western Europe, as well as jihadism in general. Indeed, in 2011 there was widespread optimism among European security agencies due to the perception that jihadism had become a spent force, which was no longer able to perpetrate deadly attacks in Western Europe. However, this perception was completely shattered when the Arab Spring deteriorated into a jihadist front and the civil war in Syria became an unprecedented magnet for jihadist groups and foreign fighters. The Syrian conflict became a game changer for jihadism and the birth of Islamic State of Iraq and Syria (ISIS) within the war increased its international echo.</p>
<p>The data this project is based on was retrieved from the Global Terrorism Database, an open-source database maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism at the University of Maryland, College Park, in the United States. As of October 2019, the database includes information on over 190,000 terrorist events occurred around the world from 1970 to 2018.</p>
<p>&nbsp;</p>
<h2>Preliminary Analysis</h2>
<p>&nbsp;</p>
<p>Firstly, I will index the dataset and got only the attacks perpetrated in Western Europe between January 2011 and December 2018. As a preliminary analysis, I would like to compare the number of attacks carried on by known perpetrators and the number of attacks perpetrated by unknown attackers.&nbsp;</p>

<img width="500" alt="total attacks" src="https://user-images.githubusercontent.com/54607208/72084764-17151500-32d2-11ea-9e8c-20c055de1e3e.PNG">

<p>Then, I will rule out all the attacks perpetrated by unknown attackers and divide the known groups in two macro categories: ‘Islamist/Jihadist’ and ‘Non-Jihadist’. As I did with know and unknown groups, I will compare the number of attacks carried on by Islamist/Jihadist and Non-Jihadist.&nbsp;</p>

<img width="500" alt="number of attacks 2011-2018" src="https://user-images.githubusercontent.com/54607208/72084808-2eec9900-32d2-11ea-96cf-de617730a0fe.PNG">

<h2>Comparison by Country</h2>
<p>From this section on, I just consider the attacks perpetrated by known terrorist groups. In this first section, I will compare the countries that have been affected the most by the attacks of both groups.&nbsp;</p>

<img width="650" alt="countries jihad" src="https://user-images.githubusercontent.com/54607208/72086212-8855c780-32d4-11ea-8995-513f5701088f.PNG">

<img width="650" alt="countries non jihad" src="https://user-images.githubusercontent.com/54607208/72086242-93105c80-32d4-11ea-899e-b5c4dec595db.PNG">

<p>Next, I will plot some maps that display the locations of the attacks.&nbsp;
</p>
<p>The following map displays the locations of the jihadist attacks:
  
<img width="600" alt="map 1 jiha" src="https://user-images.githubusercontent.com/54607208/72087189-fea6f980-32d5-11ea-8628-8835077abb43.PNG">

<p>The following map displays the locations of the non-jihadist attacks:
  
<img width="600" alt="map 2 non jh" src="https://user-images.githubusercontent.com/54607208/72087224-0e264280-32d6-11ea-84ef-3b140acbb177.PNG">

<p>The following density map displays the locations of the jihadist attacks:
  
<img width="600" alt="map 3 jih" src="https://user-images.githubusercontent.com/54607208/72087248-1b433180-32d6-11ea-8644-64015ffc22d8.PNG">
  
<p>The following density map displays the locations of the non-jihadist attacks:
  
<img width="600" alt="map 4 non j giusta" src="https://user-images.githubusercontent.com/54607208/72087270-27c78a00-32d6-11ea-9598-ae7f98818985.PNG">

<h2>Comparison by Modus Operandi</h2>
<p>In this second part of the project, I will compare the&nbsp;various modus operandi whereby jihadist and non-jihadist terrorist perpetrated their attacks.&nbsp;I will create a new modus operandi called ‘Mixed Type’ if the terrorists used more than one modus operandi to carry on their attack.</p>

<img width="500" alt="mod ope jih" src="https://user-images.githubusercontent.com/54607208/72086284-a3283c00-32d4-11ea-9bc6-cd96f4e24288.PNG">

<img width="500" alt="non jiahd mod op" src="https://user-images.githubusercontent.com/54607208/72086421-e2ef2380-32d4-11ea-8137-90ad8b439a2d.PNG">

<h2>Comparison by Target</h2>
<p>The third section will compare the targets hit by Islamist groups and Non-Jihadist groups. Similarly to what I did for the section on modus operandi, I will create a new target ‘Multiple Targets’ if the terrorist attack hit different types of targets.&nbsp;</p>

<img width="650" alt="targets jihad" src="https://user-images.githubusercontent.com/54607208/72086477-fdc19800-32d4-11ea-88ce-90bdcc9b93cd.PNG">

<img width="650" alt="targets non j" src="https://user-images.githubusercontent.com/54607208/72086503-087c2d00-32d5-11ea-8abe-f81c083d397f.PNG">

<h2>Comparison by Killings</h2>
<p>The fourth part will examine and compare the fatalities that resulted from the attacks of the two groups.</p>

<img width="500" alt="number of attacks 2011-2018" src="https://user-images.githubusercontent.com/54607208/72086549-1762df80-32d5-11ea-8c4a-99a51a618437.PNG">

<img width="650" alt="deaths" src="https://user-images.githubusercontent.com/54607208/72086573-221d7480-32d5-11ea-8c16-bd42e92f412e.PNG">

<img width="650" alt="fatalities over time" src="https://user-images.githubusercontent.com/54607208/72086620-33ff1780-32d5-11ea-80f6-c65c97c8323e.PNG">

<h2>Conclusions</h2>
<ul type="disc">
  <li>Countries with the highest number of second-generation Muslim experienced more Jihadist terrorism than others. It will likely be this way in the future as well although there are other important factors that might influence the rise of Islamist extremism.</li>
  <li>Divided countries and/or countries with serious socioeconomic problems experienced more Jihadist terrorism than others. It will most likely remain this way in the future as well.</li>
  <li>Armed assault is the preferred modus operandi of Jihadist terrorists, as their goal is usually to carry out mass casualties.</li>
  <li>Bombing/Explosions and facility and infrastructure attacks are the preferred modus operandi of Non-Jihadist terrorists. Non-jihadist attackers tend to carry out more symbolic attacks, to deliver a message or to threaten people and institutions. Facility and infrastructure attacks such as incendiary attacks and vandalism are very common among anarchist and political extremists to warn, intimidate and scare.</li>
  <li>Jihadist attacks are overall more complex and well-articulated than Non-jihadist attacks, as indicated by the fact that Jihadists have often carried out attacks combining different types of attacks and hitting multiple targets.</li>
  <li>Private citizens are the preferred target for both groups as they are the easiest targets to hit since for the state it is realistically impossible to protect every single person.&nbsp;It will always be this way.</li>
  <li>Police and the military are common targets for both groups. They represent the armed branch of the state all terrorist fight against.</li>
  <li>Jihadists have no interest in targeting governmental targets, whereas Non-jihadists target the government frequently with symbolic attacks.</li>
  <li>Jihadist attacks are high-lethality strikes, whose goal is killing indiscriminately the largest number of people possible. Non-Jihadists usually carry out symbolic strikes, and their goal is to dramatize and call the attention to their ideals.</li>
  <li>The frequency of attacks and the number of deaths of both Jihadist and Non-Jihadist attacks have been declining. This is due to an improved effort of intelligence and law enforcement agencies and some external facts, such as the partial defeat of ISIS in Syria. In the short term, both the frequency of attacks and the number of deaths will likely keep following this trend.</li>
</ul>


