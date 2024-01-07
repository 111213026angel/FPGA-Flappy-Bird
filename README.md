# FPGA-Flappy-Bird

-USE FPGA 8x8 led to create a Flappy Bird game

-INPUT：
SW S1 控制鳥往上移動(player1) S2 重新開始(restart) 
指撥 ON=HI 0：簡單模式 1:困難模式 (mode)

-OUTPUT：
七段顯示器 紀錄遊玩秒數
8x8led 遊玩畫面
蜂鳴器  撞到東西時會響 (beep)

-以下是PIN腳
COMM[0]	Location	PIN_55
COMM[1]	Location	PIN_58
COMM[2]	Location	PIN_59
COMM[3]	Location	PIN_60
DATA_B[0]	Location	PIN_72
DATA_B[1]	Location	PIN_73
DATA_B[2]	Location	PIN_74
DATA_B[3]	Location	PIN_75
DATA_B[4]	Location	PIN_76
DATA_B[5]	Location	PIN_77
DATA_B[6]	Location	PIN_79
DATA_B[7]	Location	PIN_80
DATA_G[0]	Location	PIN_64
DATA_G[1]	Location	PIN_65
DATA_G[2]	Location	PIN_66
DATA_G[3]	Location	PIN_67
DATA_G[4]	Location	PIN_68
DATA_G[5]	Location	PIN_69
DATA_G[6]	Location	PIN_70
DATA_G[7]	Location	PIN_71
DATA_R[0]	Location	PIN_135
DATA_R[1]	Location	PIN_136
DATA_R[2]	Location	PIN_137
DATA_R[3]	Location	PIN_138
DATA_R[4]	Location	PIN_141
DATA_R[5]	Location	PIN_142
DATA_R[6]	Location	PIN_143
DATA_R[7]	Location	PIN_144
player1	Location	PIN_54
CLK	Location	PIN_22
restart	Location	PIN_53
mode	Location	PIN_52
b	Location	PIN_125
c	Location	PIN_126
d	Location	PIN_127
e	Location	PIN_128
f	Location	PIN_129
g	Location	PIN_132
com[0]	Location	PIN_120
com[1]	Location	PIN_121
a	Location	PIN_124
beep	Location	PIN_119
