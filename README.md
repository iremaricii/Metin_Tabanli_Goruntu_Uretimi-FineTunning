# Metin_Tabanli_Goruntu_Uretimi-FineTunning

Bu projede, Stable Diffusion modelini kullanarak metin girdilerinden yüksek kaliteli görseller üretmeyi ve özel veri setleri ile ince ayar (fine-tuning) yapmayı amaçladık. Projede hem temel model kurulumu hem de gelişmiş teknikler (Textual Inversion, LoRA, ControlNet/inpainting, CLIP Guidance) uygulanmıştır. Ayrıca, son aşamada üretilen görseller FID gibi objektif metriklerle değerlendirilmiş ve modelin üretim sürecini kullanıcı dostu hale getirmek için Gradio tabanlı arayüz ve FastAPI tabanlı web API geliştirilmiştir.

ControlNet kullanılarak, belirli alanlarda detaylandırma yapılan görseller elde edilmiştir. Aşağıdaki şematik örnek, inpainting sürecini özetlemektedir:

![image](https://github.com/user-attachments/assets/81b11ad4-dc7a-4b9d-abd3-feb25b1057d6)

---------------------
![image](https://github.com/user-attachments/assets/866a2230-dd9e-42bd-a393-919d52c5423a)

------------------


Metin girdisi alan, Stable Diffusion modelini çalıştıran ve üretilen görselleri gösteren bir arayüz geliştirilmiştir.










![image](https://github.com/user-attachments/assets/6501e957-ab23-4dbf-9fe8-97351d94af77)


--------------------
![image](https://github.com/user-attachments/assets/191de49e-01e3-4e15-a7c4-424065f55822)
