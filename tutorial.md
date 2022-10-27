### @codeStart players set @s makecode 0
### @codeStop players set @s makecode 1

### @hideIteration true 
### @flyoutOnly 1
### @explicitHints 1

# Bamboo Border

```template
player.onChat("bamboo", function () {
    agent.setItem(BAMBOO, 64, 1);
    for (let index = 0; index < 16; index++) {
        agent.place(DOWN);
        agent.move(FORWARD, 1);
    }
    agent.turn(LEFT_TURN);
})
```

## Step 1
There is a starter code that we prepared for you.  Try running it first. The final goal is to plant bamboo along **4** sides of the panda's plot. 

~hint This content is hidden until the user clicks here.
  - :blank: Bullet 1
  - :mouse pointer: Bullet 2
hint~

## Step 2
Create bamboo border to save panda Jim

```blocks
player.onChat("bamboo", function () {
    agent.setItem(BAMBOO, 64, 1);
    for (let index = 0; index < 16; index++) {
        agent.place(DOWN);
        agent.move(FORWARD, 1);
    }
    agent.turn(LEFT_TURN);
})
```
