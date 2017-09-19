## Free Pro License for 2 months

**Why**: Better Code is Better Business. Introducing Better Code Hub to the Agile Greece conference 2017. 

**What**: [Better Code Hub](https://bettercodehub.com) - a [GitHub Marketplace app](https://github.com/marketplace/better-code-hub) that gives developers a definition of done for code quality. You can improve your public or private codebase while using Better Code Hub in your CICD pipleine to get refactor candidates. 

**When**: Friday, September 22nd 2017 during the [Agile Greece Summit 2017](https://http://agilesummit.gr).

**Where**: The SIG & PeopleCert booth at [Proorismos Papstratos](http://agilesummit.gr/venue-proorismos-papastratos/).


### How to get your free PRO license

Come visit the SIG booth and share your personal GitHub handle. 

### How to get started with better Code Hub! 

With Better Code Hub, you can check how good your team's code scores compared with the state of the art in software engineering. If Better Code Hub says you're compliant (✅) then it means you're performing like the top teams in the industry. It checks for compliance with 10 guidelines for Maintainable Software. 

![10 guidelines](https://cdn-images-1.medium.com/max/1440/1*TS-ZTeI7sQS7dy_AlMqSXQ.png)

The guidelines are described in full in the book [“Building Maintainable Software”](http://shop.oreilly.com/product/0636920049159.do) Compliance to the guidelines is derived from the Software Improvement Group's industry benchmark (8 billion lines of code, over 180 technologies). 

## Supported Languages

![Languages](languages.png)
For a full list of the supported technologies, check [here](https://bettercodehub.com/docs/configuration-manual).

## Zero set-up time

Using Better Code Hub is easy. Just head over to [bettercodehub.com](https://bettercodehub.com) and login with your GitHub account. You'll then see your repos, and you can start an analysis clicking the ▶️ button. 

If you want Better Code Hub to run for every Push and Pull Request on your repo, click the ⚙ icon and toggle the switch:

![githubflow](https://cdn-images-1.medium.com/max/720/1*N4wz389i80UbXKnjSp_QoA.png "Activate GitHub flow")

## Excluding files from analysis

Better Code Hub analyses all the code that is in your repository. This might include all the external libraries that you use. 

First do an initial analysis of your repository, so the "Analysis configuration" option becomes available. Then you can exclude these files by creating a **.bettercodehub.yml** configuration file located in the root of your repository. The code that goes into this file, can be generated with the "Analysis configuration" page which contains the following widget:

![BCH Config](yml.png)

You can find this page by first clicking on the ⚙ icon and then clicking on "Analysis configuration". 

The resulting configuration file might look like:

~~~~
exclude:
- /mylibrary/src/.*
component_depth: 1
languages:
- java
- solidity
~~~~

Of course, you can create the configuration file directly, and place it to the root of your repository. For details check the [configuration manual](https://bettercodehub.com/docs/configuration-manual).

* **Solidity** in your repo? To analyze that languange too please add [- solidity] to the configuration file as shown in the example above. 


## Support and PRO License 

* If needed, get support through bettercodehub@sig.eu

## We'd like to hear from you
Don't hesitate to send us feedback at [bettercodehub@sig.eu](mailto://bettercodehub@sig.eu]). 

**Let's build some great software** 😊

Go, go, go and see you at Voxxed Days Athens! 

[Yiannis](https://github.com/ykanell) and [Michiel](https://github.com/michielcuijpers)

