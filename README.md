# WP Template
Since the <a href="https://roots.io/" title="Roots Team" target="_blank">Roots</a> team works quite fast and releases new versions farely often, I've decided to store the version I feel comfortable to build projects with. I recommend that you would do the same, if you wish to use Trellis for your Wordpress projects. 

I've been using this repository as a base for multiple Wordpress projects that I have build. For example: <a href="https://wptipster.com/" target="_blank" title="WPTipster - Improve your Wordpress skills">WPTipster</a>, a site that provides tips & guides to Wordpress is build on top of this repository. 

To see where the development is currently going with Trellis, visit the Roots website for further information (link in the beginning of the repository). 

## File structure
All the files related to your Wordpress, will be under the site/ folder. Files related to environments and deploys are under trellis/ folder. 

### Sage Starter Theme
Currently I've been using the version 8.4.1 and this version is also included in this repository. Because the new theme has a little bit of different tasks to execute on deploy, you need to change the deploy hooks for the newer Sage versions. Once the new 9 version will become more stable, I will most likely switch to using that. If you wish to still continue with this setup, save this repository.

### Development
Development environment uses the same Ubuntu 16.04 machine, that will be in use on the live server as well. Under both folders, you will find README files that will include the requirements and further information. 

## Hosting 
I've been using Digital Ocean (Roots recommended), Vultr and Amazon for hosting, but you can run the deploy your Wordpress site to every Ubuntu 16.04. If you are building your first project with Trellis, I would recommend deploying it to Digital Ocean or Vultr. Amazon is a little bit trickier and in needs more configuring in the server, where as both Digital Ocean and Vultr are quite straight forward. 