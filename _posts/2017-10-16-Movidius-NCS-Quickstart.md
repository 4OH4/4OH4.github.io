---
layout: post
title: Getting started with the Movidius Neural Compute Stick
---

Now that the [Movidius NCS](https://developer.movidius.com/) has TensorFlow and Raspberry Pi support, I thought it was time to really see what it was capable of. This is a quick guide to getting started with the Movidius stick, and running some of the examples. It's based around a clean install of Ubuntu 16.04 LTS.

![_config.yml]({{ site.baseurl }}/images/movidius.jpg)

The [Developer Center](https://developer.movidius.com/start) covers the basics. Here's what I did:

    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get install git
    
    mkdir -p ~/workspace
    cd ~/workspace
    git clone https://github.com/movidius/ncsdk.git
    cd ~/workspace/ncsdk
    make install
    
Now plug in the Movidius NCS stick. Run the included examples:

    make examples



To follow: running inference, and TensorFlow
