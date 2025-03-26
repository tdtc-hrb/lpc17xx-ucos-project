This version of the architecture in UCOS V2.86

                            1) identifier "OS_TASK_TMR_PRIO" undefined.
                                在app_cfg.h增加其定义


                            2）不使用application hook   
                                设置OS_APP_HOOKS_EN为0;
