import time
import keyboard

def press_w_twice_every_2_seconds(duration):
    start_time = time.time()
    while time.time() - start_time < duration:
        keyboard.press("w")
        keyboard.press("w")
        time.sleep(0.5)  # İki "w" tuşuna basma aralığı
        keyboard.release("w")
        keyboard.release("w")
        time.sleep(1.5)  # Toplam 2 saniyede bir "w" tuşuna basma

if __name__ == "__main__":
    duration_seconds = 100
    press_w_twice_every_2_seconds(duration_seconds)
