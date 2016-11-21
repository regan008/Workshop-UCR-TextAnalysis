---
title: "Getting Started"
lastmod: 2015-12-23
date: "2012-04-06"
type: page
weight: 06
---

## Downloads

<div class="row">
  <div class="col-sm-4">
    <div class="card card-block">
      <h4 class="card-title">Java</h4>
      <p class="card-text">Before downloading Voyant, you will need to download Java if you don't already have it. If you do have Java installed, you should still download and update your version.</p>
      <a href="#" class="btn btn-outline-primary">Get Java</a>
    </div>
  </div>
  <div class="col-sm-4">
  <div class="card card-block">
    <h4 class="card-title">Voyant Server</h4>
    <p class="card-text">This is a rather large download. If you can't get it to download, I will have copies available on flash drives.</p>
    <a href="#" class="btn btn-outline-primary">Get Voyant Server</a>
  </div>
  </div>
  <div class="col-sm-4">
  <div class="card card-block">
    <h4 class="card-title">Sample Data</h4>
    <p class="card-text">This sample data has been curated from a larger corpus. It contains the entirety of the physical education publication <i>Mind and Body</i> which ran from 1882 until 1936.</p>
    <a href="#" class="btn btn-outline-primary">Get the Data</a>
  </div>
  </div>
</div>
## Installation
Although Voyant Tools is a web based set of tools, we'll be downloading it and running it locally. Downloading Voyant to your own computer brings a number of advantages but the main impetus for doing so today is so that we won't encounter loading issues resulting from overwhelming the server. However using Voyant locally also means that your texts won't be cached and stored on the Voyant Server, it allows you to restart the server if you encounter problems, and it allows you to work offline, without an internet connection.

 1. [Install or Update Java](https://www.java.com/en/)
 2. Download [Voyant Server from Github](https://github.com/sgsinclair/VoyantServer/releases/tag/2.2.0-M2) (If the download doesn't work for you, I have the file on a flash drive)
 3. Unzip the Voyant Server Package. The resulting folder of files should look like this:
 {{< figure src="images/voyant-server-zip-contents.png" >}}
 4. Double click the VoyantServer.jar file. When you open this file a new window (see image below) will pop up with numerous server controls. If you're curious about what these all mean you can read about the options in the documentation for the Voyant Server. However, in short, this window begins to launch a server which will generate the Voyant tools interface.
 {{< figure src="images/voyantserver-controls.png" >}}
 5. Once the server has booted up a new browser window will open.
 {{< figure src="images/voyantserver-home.png" >}}
 ** If your default browser is Chrome you'll need to paste the address into a new window in a different browser. Both Safari and Firefox work. The default address should be: http://127.0.0.1:8888/
