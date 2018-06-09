### The PeachesAhead Project

<img src="https://image.ibb.co/dPnWL8/giphy.gif" style="background:none; border:none; box-shadow:none;">

##### A Factom Hackathon Presentation 

---

## Project Backstory

Factom Hackathon Question - How does Blockchain enable the world to bypass paper?

- [ ] Major goal - paperless supply chain demonstration, running on a blockchain network or 2..

Answer: 


Security
- [ ] A visual way of tracking / monitoring peaches from farm(s) to the distributor(s) to the stand(s).
- [ ] Stand selling peaches that can be verified authentic. 

Major Considerations:
Time, Functionality, Security, Savings, Effort

The Big Questions: 
How does Blockchain enable the world to bypass paper?

---

## Main Priorities

Savings
- [ ] A major goal of the project

Security
- [ ] A visual way of tracking / monitoring peaches from farm(s) to the distributor(s) to the stand(s).
- [ ] Stand selling peaches that can be verified authentic. 

Major Considerations:
Time, Functionality, Security, Savings, Effort

The Big Questions: 
How does Blockchain enable the world to bypass paper?

---

## More stuff

Participants will be asked to use the Factom blockchain to create solutions using data from the Factom Blockchain instead of what would be traditionally stored on paper.

Scale & Complexity 
How useful is the solution?

Innovation
How original is the solution?

Quality of Implementation
Does the solution make good use of the Factom protocol?

Presentation
Was your presentation clear and informative?

@fa[arrows gp-tip](Press F to go Fullscreen)

@fa[microphone gp-tip](Press S for Speaker Notes)


---

## Even More stuff

@fa[list-alt gp-tip](Factom Powered Verification Layer)
Verification of "REAL" fredericksburg peaches from an Orchard in Fredericksburg, Texas

<img src="http://www.texaspeaches.com/images/heading03.jpg" style="background:none; border:none; box-shadow:none;">

---

#### The Garbage In, Garbage Out Dillema

We may want to certify, for example, that a consumer is buying fredericksburg peaches. <br>
If the first step of the process involves a farmer stating that their peaches are grown in fredericksburg, TX, but this is not true, then the blockchain is providing an indelible record that the peaches originate from a "false" location. 

Proposed Solution(s): Proof of Location
FOAM [https://www.foam.space/]
Platin [https://platin.io/]

---

## Main Goals

- [Plan of Attack](https://hackernoon.com/building-your-own-bitcoin-satellite-node-6061d3c93e7) |
- [Team Milestones](https://medium.com/@notgrubles/building-your-own-bitcoin-satellite-node-part-2-software-installation-a94a0b85d089) |
- [Documenting](https://hackernoon.com/building-your-own-bitcoin-satellite-node-part-3-dish-alignment-1306b4c21326) |
- Uplink Off-line Blockchain Sync Testing |
- Test Transaction's and webApp showing |
- Custom Logo, 3rd Party Review, and Footnotes |

---?code=sample/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---

## Project Resources & Help

- [PoC Blockchain + Agriculture Demonstration Code](https://github.com/AravindNico/blockchain_agri_usecase)
  + [How Blockchain Can Revolutionize Agricultural Supply Chain Part 1](http://radiostud.io/blockchain-can-revolutionize-agricultural-supply-chain-part-1) 
  + [How Blockchain Can Revolutionize Agricultural Supply Chain Part 2](http://radiostud.io/blockchain-can-revolutionize-agricultural-supply-chain-part-2)
- [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

## Test Results

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details here.</a>
</div>
<div class="right">
    <ul>
        <li>Obstacles</li>
        <li>Team Decisions</li>
        <li>Changes in plan</li>
        <li>Future upgrades</li>
        <li>credits</li>
    </ul>
</div>

30 mins setting up factom api, auth issues, chain creation, creating an entry, the problems encountered, the olution involved.
so with api auth, pretty easy, obtain key, curl params;;
chain creation was a little trickier, took 2 modifications;;
adding entries,

curl --request POST \
  --url https://apiplus-api-sandbox-testnet.factom.com/v1/chains/04fc7129d25d2d3068eea5c8a51413d2b42ebbb789229653401091a3915918f2/entries \
  --data '{"external_ids":["UGVhY2ggU3RhbmQgIzEgTG9jYXRpb24="],"content":"MzAuMzgzNTg2MywtOTguMDg1MDczNg==","callback_url":"null","callback_stages":"factom"}'
  
{"errors":{"detail":"Bad request"}}



---

### Questions?

<br>

@fa[twitter gp-contact](@TeamPeachesAhead)

@fa[github gp-contact](TeamPeachesAhead)


---?image=assets/image/gitpitch-audience.jpg&opacity=100

@title[Get Involved!]

### Get started helping us out!

![Discord](https://github.com/unibitlabs/vigilant-barnacle/blob/master/assets/image/discord.png?raw=true)
![Twitch](https://github.com/unibitlabs/vigilant-barnacle/blob/master/assets/image/twitch.png?raw=true)
![YouTube](https://github.com/unibitlabs/vigilant-barnacle/blob/master/assets/image/youtube.png?raw=true)
![FaceBook](https://github.com/unibitlabs/vigilant-barnacle/blob/master/assets/image/find-us-on-facebook.png?raw=true)

---


![YouTube](https://www.youtube.com/embed/_c691Myl8sA)

