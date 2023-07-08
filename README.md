[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/isPhTOcA)

# Personal Website

This is my second personal website better than before (hope so) in this assignment i'm not talking about my personal website but about how to deploy a website with costume domain name
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)  
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)   
![PhotoShop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)    
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)

# Branching Structure

![Branching Structure](ScreenShot/Untitled%20Diagram.jpg)

## Git Clone, Branching
### Step 1
This Process How To Get You Repository From Github To Local Using Git Clone Don't Forget To Install GitBash If You Using Windows OS
![Git Clone](/ScreenShot/1.%20git%20clone.png)
### Step 2
If You See This On GitBash It Mean Git Clone Success
![Git Clone Success](ScreenShot/2.%20git%20clone%20success.png)
### Step 3
Add Git Branch And Open Your Vscode As You Can See On The Second Image I Want To Make Branching Main-> Develop -> Front_End | Back_End. I Want To Make Two Branches On Develop So I Need To "Git Checkout Develop" So I Can Make Branch On Develop Branch (See First Image In The Pink Circle That Mean You On Develop Branch)
![Git Branch](/ScreenShot/3.%20add%20branch%20via%20gitbash.png)
### Step 4
If Success To Create Branch You Can See On Git Branch. Open Your Vscode To Publish Your Branch To Github As You Can See On The Second Image In The Blue Circle It Say Publish To Github If You Click That It Will Be Automatically Publish Branch To Your Github You Can Check It On Branches Menu
![Add Git Branch FE dan BE](ScreenShot/4.%20make%20fe%20and%20be%20branch%20on%20develop.png)
![Upload Branch](/ScreenShot/5.%20upload%20branch%20to%20github.png)

After Publish Branch to Github open your Github So You Can See The Branch You Added
![Branch Menu](/ScreenShot/5.%20branches%20menu.png)
![Branch Added](ScreenShot/5.%20see%20our%20branch.png)

# NETLIFY DEPLOY

### Step 1
You Have To Login In To [Netlify](https://www.netlify.com/) Using Your Github Account and Go To Menu New Site and choose **Import an Existing Project**
![Netlify Github Signin](/ScreenShot/6.%20add%20new%20site%20from%20github.png)

### Step 2
After you choose import an existring Project choose from github so netlify can connect to your organization or repository on your github
![Netlify and Github](ScreenShot/7.%20choose%20github.png)

### Step 3
Choose Branch And I Choose Brain Main For Production On Netlify (It Mean When You Push New Code On Main Branch, The Website Will Change Automatically So You Don't Have To Deploy Manually) Scroll Down And You Can See Deploy Site It Will Automatically Deploy To Your Netlify like the second picture
![Choose Main Branch](/ScreenShot/10.%20choose%20branch%20scroll%20and%20see%20deploy%20site.png)
![First Time Deploy](/ScreenShot/10.%20main%20first%20time.png)

# Push, Pull, Merge

## Push to Front_End Branch

### Step 1
Time To Push To Front End In The Orange Circle Is Your Folder From Repository You Can Add Some File You Need. In The Blue Circle As You Can See On Branch Menu You See 4 Branches (Main, Develop, Front_End And Back End) Which We Have Previously Created In GitBash. Don't Forget Before You Push You Have To See Where Are You At (You Can See In The Yellow Circle) If You On Branch Main You Have To Click In The Pink Circle To Move To The Branch Target. After You Make Sure You Are On The Branch Front_End You Can Commit To Your Repo On Branch Front_End Don't Forget To Leave Some Message And You Can Click Commit. After Commit You Can See Sync Button You Can Click It And Poof Files Will Automatically Update To Your Branch.
![Push Front_End Branch](/ScreenShot/12.%20front%20end%20branch.png)

**Tadaaaaa It Will Show On Your Branch**
![Show File on Github after Push](/ScreenShot/13.%20front_end%20branch.png)

### Step 2
And It's Time To Merge With Develop Branch. As You Can See In This Picture We Want To Merge With Develop Branch Don't Forget To Change Branch We Want To Merge (Like In The Blue Circle I Want To Merge With Develop I Change To Branch Develop) Be Careful Before You Merge You Have To Read Carefully Because The Default Is Main And It Will Be Merge With Main. After We Make Sure About Everything You Can Make A Pull Request (Like In The Red Circle You Just Have To Click It).
![Pull Request to Develop](/ScreenShot/14.%20pull%20request%20to%20develop.png)

### Step 3
As You Can See In This Page We Can See Whether There Is A Conflict Or Not If All Green You Can Go To Next Step If There's A Red It Means Have A Conflict On Something And You Have To Make Sure Again Like In The Yellow Circle Target : Develop Branch From : Front_End Branch. And You Can Put Some Comment Too Before You Merge To Pull Request If You Scroll Down You Can See The Comment Column But Sorry That Is An Image You Can't Scroll It Down.
![Merge to Develop](/ScreenShot/15.%20pull%20request%20front%20end.png)

## Push to Back_End Branch

### Step 1
Now It's For Backend Time. Open You Vscode Again And Now You Have To Choose Back_End Branch (As You Can See I On Main Bran Like In The Pink Circle) As You Can See I Add Some Javascript File After Everything Done You Can Push Like We Did Before In Front End Push.
![Add Some JS File](/ScreenShot/16.%20add%20some%20js.png)

### Step 2
It's Time For Pull Request From Back_End Branch To Develop Branch Like This Image
![Pull Request Back End](ScreenShot/17.%20confirm%20merge%20backend%20to%20develop.png)

### Step 3
And You Can See Complete Merge On Develop Branch. You Have To Make Sure Every Single Thing Before You Merge To Main. If Everything Is Complete We Can Proceed To The Next Step To Pull Request To Main
![Develop Branch](/ScreenShot/18.%20file%20on%20develop.png)

### Step 4
As Same Like Before You Can See On This Page You Can Put Some Comment Before You Merge To Main
![File on Develop Branch](/ScreenShot/19.%20merge%20develop%20to%20main.png)

**And Voilaaaa Now Develop Branch Just Merge With Main Branch**
![Main Branch](/ScreenShot/20.%20all%20merge.png)

### Step 5
Open Netlify On Your Browser You Can Click In The Blue Circle And It Will Open Your Browser To Preview Latest Update On You Github Main Branch
![Netlify Update](/ScreenShot/21.%20open%20netlify%20to%20deploy.png)
![Update Main Branch](/ScreenShot/21.%20before%20change%20domain.png)

# Netlify, Costume Domain Name, Setting Name Severer, Cloudflare DNS Setting

## Buy Costume Domain and Setting Server Name
Now Time To Change Domain Name. First Thing You Have To Buy Domain Name. Just Buy It From [Niagahoster](https://www.niagahoster.co.id/) And It Will Show Like First Image. After You Buy Domain Name You Can Put Server Name On It I Put Server Name From [Cloudflare](https://www.cloudflare.com/) Before You Put Server Name From Cloudflare To Niagahoster You Have To Signup On Cloudflare So You Will Get Server Name And Put It On Niagahoster.
![Buy Costume Domain Name](/ScreenShot/22.%20buy%20domain%20name.png)

**Before Setting Server Name**
![Before Setting Server Name](/ScreenShot/22.%20before%20change%20name%20server.png)

**After Setting Server Name**
![After Setting Server Name](/ScreenShot/22.%20after%20change%20name%20server.png)

## Cloudflare DNS Setting
Now Go To [Cloudflare](https://www.cloudflare.com/) And You Have To Setting Your DNS So It Will Connect To Your Netlify This Is An Example Of DNS External Setting Choose DNS Menu On Cloudflare And Add Record. As You Can See In This Image It Have Type Column, Name And Target. You Just Choose Cname On Type Column, On Name Column You Just Have To Enter The Domain Name That Was Previously Purchased From Niagahoster, And Target Column Enter Domain Name From Netlify. Add Record Again But This Time You Enter The Name Column With Www And Target Is Your Domain Name From Niagahoster. And It Will Show Like This Image. You Just Have To Wait Max 24 Hours And Don't Forget To Check Your Email Cloudflare Will Sent You Verify Account.
![Setting DNS](/ScreenShot/23.%20setting%20dns%20cloudflare.png)

## Check DNS Status
Check Home Page On Cloudflare If There's Nothing Wrong, You Can See Your Domain Name Active Like This Picture

**Status Pending**
![DNS Status Before](/ScreenShot/24.%20before%20active%20link%20on%20cloudflare.png)

**Status Active**
![DNS Status Active](ScreenShot/24.%20active%20link%20on%20cloudflare.png)

## Setting Costume Domain And DNS Status
Back To Netlify And Go To Domain Setting You Just Have To Add You Domain Name From Niagahoster And You Have To Wait Like 1 Hour Before Your Domain Netlify (The Random One) Change To Domain Name From Niaga Hoster. And You Can See DNS Status on Netlify

![Add Domain](/ScreenShot/25.%20add%20domain%20netlify.png)

**You Can See DNS Status That We Have Created Before On Cloudflare**
![DNS Status On Netlify](/ScreenShot/24.%20before%20active%20link%20on%20cloudflare.png)

## END

Annddd The Last Thing You Can Open Your Browser And Enter Your Costume Domain Name From Niagahoster Voilaaaa It Will Look Like This
![Costume Domain Active](/ScreenShot/26.%20domain%20change.png)

## Credit

Hilman Syarifuin Fadilah
[www.onlytest.site](https://www.onlytest.site)












