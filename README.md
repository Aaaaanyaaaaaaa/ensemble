1) First step is about collecting bbox and ious for each picture for Maira and MedRPG
2) Draw two types of bboxes: without and with. Without means without ground truth and with is with ground truth
3) On the third step we ask GPT two questions: What bbox (maira and rpg) better describes the body part (without file). The seond question is what bbox among gt maira and medrpg describes better body part (with file). We also compute metrics in those both

Table with results

![table with results](https://github.com/Aaaaanyaaaaaaa/ensemble/blob/main/pictures/table_mnm.png)