Medium Blog Post :  

# Neural Style Transfer (Nöral Stil Transferi)
Neural Style Transfer ile bir temel resmin içeriği ve bir başka resmin stili birleştirilebilir. Örneğin bir modelden resminizi cubism akımı ile oluşturmasını isteyebilirsiniz. Bu konuya ilk kez A Neural Algorithm of Artistic Style makalesinde değinildi. Makaleyi okuyarak ayrıntılı bilgi edinebilirsiniz. 
Önceden eğitilmiş bir derin öğrenme modelini kullanarak bir resmin içeriğini ve stilini çıkartabiliriz. Burada içerik dediğimiz resimde belirgin olarak geçen verilerdik. Bir köpek resminde içerik köpeğin kendisidir. Stil olarak bahsettiğimiz ise resimde bulunan özelliklerin birbiriyle nasıl bir etkileşim içinde olduğudur. Hangi özelliklerin birlikte oluştuğudur. Buna daha ayrıntılı değineceğiz. 
Aşağıdaki resimde şehir resminin içeriğini, Van Gogh'un Yıldızlı Gece eserinin de stilini kullanarak NST ile yeni bir resim oluşturacağız.


![Base Image](https://github.com/burakbaga/neural_style_transfer/blob/master/images/city.jpg)
![Style Image](https://github.com/burakbaga/neural_style_transfer/blob/master/images/van.jpg)
![Generated](https://github.com/burakbaga/neural_style_transfer/blob/master/images/city_generated_at_iteration_4000.png)
