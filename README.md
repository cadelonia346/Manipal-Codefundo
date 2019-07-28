# Manipal-Codefundo
GitHub repo for codefundo - JASON PETER ANDREWS
MIT, Manipal

OVERVIEW:
  In this age of modern communication, the attention of people is entirely devoted to devices such as laptops, computers and most popularly, smartphones. And in this age, online information such as news articles, blog posts, youtube videos, and social media governs what people see and understand. The future decisions of people are completely influenced by what they see online, regardless of whether the information is true or false. These days, it is very hard to distinguish between authentic news and fake, spam or hoax news(https://www.bbc.com/news/world-asia-india-47797151). Most recently, the US presidential elections have been rumored to have been swayed by external sources:
  
  "A whistleblower has revealed to the Observer how Cambridge Analytica – a company owned by the hedge fund billionaire Robert Mercer, and headed at the time by Trump’s key adviser Steve Bannon – used personal information taken without authorization in early 2014 to build a system that could profile individual US voters, in order to target them with personalized political advertisements." (https://www.theguardian.com/news/2018/mar/17/cambridge-analytica-facebook-influence-us-election)
  
  Political parties use this complete dependence of people on the internet to their advantage.

  Using aggressive marketing, excessive advertising and even the spreading of fake news, political parties can control what the people see online, thereby, either portraying their agenda in their favor by skewing the truth or even slandering the opposition by spreading false rumors. These tactics are often used to hide the criminal history of candidates or to make the public overlook their lack of attendance in the house. Even post-election, these methods are used to confuse and mislead people as to the promises that the candidates made pre-election.

  Although these tactics may seem insignificant, they have a lasting impact, especially on the illiterate population, who constitute a major chunk of the eligible voters in India. Due to their lack of knowledge and credible sources, the people often believe these fake news reports, thus influencing their vote. This can ultimately lead to a different, perhaps subpar candidate, being elected.

  Thus, there is an urgent need for a centralized and unified service that gives the people authentic information about the candidates background criminal history, their attendance numbers as well as credible news about the candidate's promises that they made pre and post-elections.
  
  I am to achieve this by using MICROSOFT'S AZURE BLOCKCHAIN technology.
  
  
WHAT I PLAN TO BUILD: 
  My project aims to create an online freely accessible platform where users can search for information about the current political parties and their candidates. The information that will be available are:
  1. The educational qualifications of the candidates as well as their criminal history.
  2. Their attendance in the Lok Sabha/ Rajya Sabha meetings.
  3. Credible news articles about the current status of the parties' responsibilities: what has been promised vs what has been achieved.
  4. Easy access to verified YouTube videos of the Candidate's speech and public talks.
  
  
 HOW I PLAN TO BUILD THIS:
 
Gathering of information and online news articles will be done through web scraping. Web scraping will be done using python coding language and then integrated into Azure's Blockchain to create a database that provides access of structured data to the public in seamless user experience. (https://medium.com/daratus/getting-ready-for-the-launch-84df49c9ca5b)

1. Authentic sites such as the member attendance webpage ( http://164.100.47.194/Loksabha/Members/MemberAttendance.aspx ) will be used to gather all the details of the attendance and structure it into a database. The user can then search this database and get real-time information about the candidates' attendance.

2. The background qualifications and criminal history will be web scraped from the appropriate and trusted sources and then structures into an appropriate format. 
( https://www.indiatoday.in/india/story/modi-sarkar-2-0-has-22-ministers-with-criminal-cases-harsimrat-badal-richest-union-minister-1539887-2019-06-01 ) 
( https://results.amarujala.com/career-diary/union-cabinet-minister-2019-education-qualification-of-our-new-ministers )

3. Trusted news sources will be used to gather the current updates of the election and structure them according to the political party it is based on. Thus, the user can see a timeline of all the news articles about a candidate/party and check whether the previous promises made have been implemented or not. This also prevents the public from being swayed by fake spam that circulates on social media and unregulated websites.

4. If the user doesn't find the information/news article he is looking for, he can request for that certain information to be gathered. The request will result in the backend team launching a web scraping query for the data.

TECHNOLOGIES AND RESOURCES USED: (Can be updated to similar but better methods if such methods are found after Round 1 of Codefundo gets over)
1. Microsoft Azure Blockchain
2. Web scraping techniques using python
3. External news and information sources
4. Hoax detection and fact-checking services/websites to differentiate between viral spam content and real news (http://www.businessworld.in/article/Not-Sure-Of-A-News-5-Fact-Checking-Sites-You-Should-Know-About/01-04-2019-168657/)

DATASETS USED:
1. Government public databases to gather real-time data on candidates.
2. Trusted news archives that will be accessed and web scraped to gather the appropriate information.
3. Real-time websites that update details of the election process (during election time)
