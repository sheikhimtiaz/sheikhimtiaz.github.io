---
layout: projects
title: Projects
subtitle: Let a thousand flowers bloom
permalink: /projects/
---



Going to share about some of the **projects** that I have worked on.

___

Let's start with a blockquote:

> The people who are crazy enough to think they can change the world are the ones who do.

## 1. Gayeebi Lang 
A simple example language built using the Truffle API.

Playing with:

1. Combined Object-Lambda Architecture
2. GraalVM
3. Truffle Language Implementation API 

<br>


## 2. ARC Digital Signature
ARC digital signature integration with ethereum network. PoC style project done with w3.js and solidity.

Tech Stack: 
- Typescript
- Solidty
- Web3


Contributors
: Nahiduzzaman Rose
: Rezwan Rafiq

<br>


## 3. Laser Guiter 

Arduino Project - Microprocessor Lab Project

Example code:

{% highlight c++ %}
void AudioClass::prepare(int16_t *buffer, int S, int volume){
    uint16_t *ubuffer = (uint16_t*) buffer;
    for (int i=0; i<S; i++) {
        // set volume amplitude (signed multiply)
        buffer[i] = buffer[i] * volume / 1024;
        // convert from signed 16 bit to unsigned 12 bit for DAC.
        ubuffer[i] += 0x8000;
        ubuffer[i] >>= 4;
    }
}
{% endhighlight %}

<br>

## 4. And many more to come ..

<br>
<br>
<br>
<br>


Want to work on a project together? [Let's talk](https://calendly.com/sheikhimtiaz).


<!-- Hello!
I'm Sheikh Imtiaz Ahmed.
Software Engineer at [SELISE Digital Platforms][selise].
[SUBSEL][imtiaz-subsel] Research Alumni.
I love to write. Anything. Codes, Articles, Stories.
Catch me every Saturday at 06:00 PM on Weekend Commits. -->
