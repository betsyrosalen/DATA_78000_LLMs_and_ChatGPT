# Product name generator

### Generate product names from a description and seed words.

## SYSTEM

You will be provided with a product description and seed words, and your task is to generate product names.

## USER

#### Prompt

Product description: A backpacking tent

Seed words: lightweight, sturdy, roomy

#### ASSISTANT

1. UltraLiteMax Tent
2. SolidSpace Backpacking Tent
3. FeatherWeave Tent
4. Durashield Hiker Tent
5. SpaciousTrail Tent
6. LitePack Backpacking Tent
7. RobustRoom Tent
8. AirLite Hiker Tent
9. SpacePlus Backpacking Tent
10. StrongHold Trail Tent

## Code

```
import os
import openai

openai.api_key = os.getenv("OPENAI_API_KEY")

response = openai.ChatCompletion.create(
  model="gpt-3.5-turbo",
  messages=[
    {
      "role": "system",
      "content": "You will be provided with a product description and seed words, and your task is to generate product names."
    },
    {
      "role": "user",
      "content": "Product description: A backpacking tent\nSeed words: lightweight, sturdy, roomy"
    },
    {
      "role": "assistant",
      "content": "1. UltraLiteMax Tent\n2. SolidSpace Backpacking Tent\n3. FeatherWeave Tent\n4. Durashield Hiker Tent\n5. SpaciousTrail Tent\n6. LitePack Backpacking Tent\n7. RobustRoom Tent\n8. AirLite Hiker Tent\n9. SpacePlus Backpacking Tent\n10. StrongHold Trail Tent"
    }
  ],
  temperature=0.8,
  max_tokens=256,
  top_p=1,
  frequency_penalty=0,
  presence_penalty=0
)
```


## SYSTEM Default 

You are a helpful assistant.

#### ASSISTANT

Introducing our new lightweight, sturdy, and roomy backpacking tent! Designed for avid adventurers, this tent is the perfect companion for your outdoor exploration. 

Weighing in at just a few pounds, our backpacking tent is one of the lightest options available on the market. Say goodbye to unnecessary bulky gear taking up valuable space in your backpack. With our tent, you can enjoy the freedom of carrying less weight and moving effortlessly through nature.

Don't let its lightweight fool you, though. This tent is built to last. Crafted with durable materials and reinforced stitching, it is designed to withstand the harsh elements of the wilderness. Whether you encounter heavy winds, rain, or rough terrain, our tent will remain steady and secure, providing you with a reliable shelter wherever you go.

But that's not all – our backpacking tent offers ample room for utmost comfort. You'll find plenty of interior space to stretch out and relax after a long day of hiking. The clever design allows for a cozy sleeping area while still leaving enough space for storing your gear. No need to compromise on comfort or convenience during your outdoor escapades!

Furthermore, our tent features convenient storage pockets and gear loft, ensuring you can keep your belongings organized and within reach at all times. The dual

```
import os
import openai

openai.api_key = os.getenv("OPENAI_API_KEY")

response = openai.ChatCompletion.create(
  model="gpt-3.5-turbo",
  messages=[
    {
      "role": "user",
      "content": "Product description: A backpacking tent\nSeed words: lightweight, sturdy, roomy"
    },
    {
      "role": "assistant",
      "content": "Introducing our new lightweight, sturdy, and roomy backpacking tent! Designed for avid adventurers, this tent is the perfect companion for your outdoor exploration. \n\nWeighing in at just a few pounds, our backpacking tent is one of the lightest options available on the market. Say goodbye to unnecessary bulky gear taking up valuable space in your backpack. With our tent, you can enjoy the freedom of carrying less weight and moving effortlessly through nature.\n\nDon't let its lightweight fool you, though. This tent is built to last. Crafted with durable materials and reinforced stitching, it is designed to withstand the harsh elements of the wilderness. Whether you encounter heavy winds, rain, or rough terrain, our tent will remain steady and secure, providing you with a reliable shelter wherever you go.\n\nBut that's not all – our backpacking tent offers ample room for utmost comfort. You'll find plenty of interior space to stretch out and relax after a long day of hiking. The clever design allows for a cozy sleeping area while still leaving enough space for storing your gear. No need to compromise on comfort or convenience during your outdoor escapades!\n\nFurthermore, our tent features convenient storage pockets and gear loft, ensuring you can keep your belongings organized and within reach at all times. The dual"
    }
  ],
  temperature=1,
  max_tokens=256,
  top_p=1,
  frequency_penalty=0,
  presence_penalty=0
)
```