# Botty McBotface #

**Release:** v0.3 | **Testing:** v0.3


Hello, there! This is Botty McBotface, an extensible Discord bot developed with the Discord.py module.

This bot began as the [BASCO CyberOps Bot](https://github.com/UofA-BASCO/BASCO-cyberopsbot) but has since grown into a platform for others to collaborate and add custom features though the use of `cogs`.

Currently, the bot is purpose-built for server users to self-administer certain roles. More features are planned for the future!

---

## How do I get set up? ###

Botty is conveniently packaged as a Docker container so it can be deployed quickly and easily.

1. Install the latest edition of [Docker](https://docs.docker.com/engine/install/) or a compatible container engine.
1. Download the container image from Docker Hub
    ```
        $ docker pull bascogroup/botty.py
    ```
1. Read and complete the [*Creating a Bot Account*](https://discordpy.readthedocs.io/en/latest/discord.html) guide.
1. The API token copied in step 7 from the bot creation guide in the previous step will be used in the next step.
1. Finally, use the command to run the bot. 
    ```
        $ docker run -d -e "BASCOBOTTOKEN=<YOUR API KEY HERE>" \
        bascogroup/botty.py:latest
    ``` 
    

## FAQs:

**Q**. Cannot run the image and getting the error `Cannot connect to the Docker daemon...Is the docker daemon running?`

**A**. Ensure the `docker` service is running according to your operating system's documentation.

**...**

---

### Contribution guidelines ###

The `main` branch representes the latest stable release, and `testing-main` is -- unsurprisingly -- the development branch. 

Feel free to contribute new features as cogs or independent modules to the repo and perform a *pull request* onto the `testing-main` branch for review.

---

### Who do I talk to? ###

* Repo owner or admin 