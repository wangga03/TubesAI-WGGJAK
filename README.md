# TubesAI-WGGJAK


Ubah Path pada baris

for (x, y, w, h) in faces:
                crop_wajah = frame[y:y+h, x:x+w]
                filename = f'dataset/wgg/wajah_{foto_ke+494}.jpg'
                cv2.imwrite(filename, crop_wajah)
                print(f"Wajah disimpan sebagai {filename}")
                foto_ke += 1

wgg -> jak
kemudian "foto_ke+494" kalau mulai dari awal bagian 494 dihilangkan biar dataset start dari 1
kalau misal udah ada baru ditambahkan misal sebelumnya udah ambil 100 dataset
brarti tinggal ditambah foto_ke + 100