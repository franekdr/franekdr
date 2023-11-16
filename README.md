void setup() {
  // put your setup code here, to run once:
Keyboard.begin();
delay(4000);
Keyboard.press(KEY_LEFT_GUI);
Keyboard.press('r');
delay(20);
Keyboard.releaseAll();
delay(50);
Keyboard.print("cmd.exe");
Keyboard.press(KEY_RETURN):
Keyboard.releaseAll();
delay(1000);
Keyboard.print("shutdown -s -t 120 -c");
delay(20);
Keyboard.print(" zamykanie ");
Keyboard.releaseAll();
Keyboard.press(KEY_RETURN):
Keyboard.releaseAll();
}
