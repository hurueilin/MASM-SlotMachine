# MASM-SlotMachine
click playgame.bat to start the program

![](https://i.imgur.com/V9K3za5.png)

![](https://i.imgur.com/QrSUoOq.png)

![](https://i.imgur.com/d304IW8.png)

## flowchart
```flow
st=>start: 起始畫面
e=>end: 破產 
op1=>operation: 規則說明
op2=>operation: 遊戲: 輸入賭金
cond1=>condition: 0<賭金<目前現金
op3=>operation: 拉霸
op4=>operation: 贏/輸金額計算
cond2=>condition: 目前現金<0

st(right)->op1(right)->op2->cond1->op3->op4(right)->cond2->e
cond1(yes)->op3(right)->op4
cond1(no)->op2
cond2(yes)->e
cond2(no)->op2
```

> author: 104403015、104403513
> for CE2012-Assembly Language and System Programming-1071 final project
