# TxtToSpeech

1)Öncelikle, .NET Framework'ün System.Speech sınıfını kullanarak ses üretebilmeniz için gerekli olan System.Speech.Synthesis nuget paketini projenize eklemelisiniz. Nuget paketini projenize eklemek için Visual Studio'da projenize sağ tıklayıp "Yönetici Nuget Paketleri" seçeneğini seçin ve arama kutusuna "System.Speech.Synthesis" yazıp, install butonuna tıklayın.
2)Daha sonra, using System.Speech.Synthesis; kod satırını projenizin en üstüne ekleyin. Bu sayede projenizde SpeechSynthesizer sınıfını kullanabileceksiniz.
3)SpeechSynthesizer sınıfını kullanarak bir ses üreteci oluşturun
4)Ses üreteci oluşturduktan sonra, üreteceğiniz sesin hangi dil ve hangi ses dosyasını kullanacağını belirleyin
5)Yazıdan sese çevirmek istediğiniz yazıyı ses üreteciye gönderebilirsiniz
