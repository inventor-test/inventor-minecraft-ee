# CodeFUN

### @hideIteration true

```template
{}
```

## agent-up 

Use ``||player:on chat||`` and  ``||agent:agent move||`` commands to program the Agent to move towards the gold plate. You can program the Agent to move **up**. When done, press the **Play** button to compile the code. Go to Minecraft to run your code in game.

```blocks
player.onChat("1", function () {
    agent.move(FORWARD, 1)
    agent.move(UP, 1)
})
```