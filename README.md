int redMain = 2;﻿
int yellowMain = 3;﻿
int greenMain = 4;﻿

int redSide = 5;﻿
int yellowSide = 6;﻿
int greenSide = 7;﻿

void setup() {﻿

  pinMode(redMain, OUTPUT);﻿
  pinMode(yellowMain, OUTPUT);﻿
  pinMode(greenMain, OUTPUT);
  pinMode(redSide, OUTPUT);
  pinMode(yellowSide, OUTPUT);﻿
  pinMode(greenSide, OUTPUT);﻿
}﻿

void loop() ﻿
  digitalWrite(greenMain, HIGH);﻿
  digitalWrite(redSide, HIGH);﻿
  delay(5000); ﻿

  digitalWrite(yellowMain, HIGH);﻿
  delay(2000); ﻿

  digitalWrite(greenMain, LOW);﻿
  digitalWrite(yellowMain, LOW);﻿
  digitalWrite(redMain, HIGH);﻿
﻿
  digitalWrite(greenSide, HIGH);﻿
  delay(5000); ﻿
﻿
  digitalWrite(yellowSide, HIGH);﻿
  delay(2000); ﻿
﻿
  digitalWrite(greenSide, LOW);﻿
  digitalWrite(yellowSide, LOW);﻿
  digitalWrite(redSide, HIGH);﻿
  delay(1000);﻿

}
