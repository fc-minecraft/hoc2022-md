### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
Агенту хватило энергии, чтобы открыть Зеленую дверь. Если ты разгадаешь, как открыть световой люк, Агент сможет зарядиться еще больше и открыть Желтую дверь.  

#### ~ tutorialhint 
Посмотри выше Агента и используй блок ``||hoc22.cursor move||``, чтобы переместить курсор над каждым люком, а затем ``||hoc22.open trapdoor||``, чтобы их открыть. Используй цветные стрелки, чтобы выбрать правильное направление движения курсора.  



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.openTrapdoor()
```
```template
    
```
```package
minecraft-hoc22=github:fc-minecraft/hoc22-ts#v0.0.4
```