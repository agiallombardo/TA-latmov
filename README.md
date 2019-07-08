# What
The technology addon "TA-latmov" was designed based off [SANS' 2018 Hunt Evil Poster](https://digital-forensics.sans.org/media/SANS_Poster_2018_Hunt_Evil_FINAL.pdf). 

This poster focuses on **lateral movement** from forensic evidence found on the source/destination endpoint after the action has occurred. Based on this, I created a series of Windows-based inputs to capture the state for threat hunting and preservation.


# How
Deploy the entire TA to the Windows universal forwarder, which already has the Splunk_TA_Windows on the local instance.

Enable the inputs and configure the intervals based on what makes sense for your environment. If not tuned correctly, there will be a ton of noise.

Deploy the entire TA to the searchheads and indexer tier (heavy forwarder, indexers) for index-time / search time operations.

# Who

*All credit of compiling the list of indicators goes to SANS: Rob Lee, and Mike Pilkington.*  I just splunkified it. 

**I am looking for additional volunteers to take this to the next level.**

## Disclaimer
Use this at your own risk, it's a proof-of-concept. 

Lastly, this was created on my own and is not supported or endorsed by my employer.
