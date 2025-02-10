# Git vs Github

## Git Tarihçesi
<p align="justify">2005 yılı öncesinde Linux işletim sistemi çekirdeği, kapalı kaynak kodlu olan BitKeeper sistemi üzerinde geliştirilmekteydi. BitKeeper’ın sahibi olan f irmanın, Linux geliştiricilerine tanımış olduğu ücretsiz kullanım iznini iptal etmesi üzerine Linus Torvalds ve diğer çekirdek geliştiricileri kendi sürüm kontrol sistemlerini geliştirmeye başlarlar. Bu yeni sürüm kontrol sistemi Git adını alır.</p>
<p align="justify">Git, günümüzde dünya çapında yazılım geliştiricilerinin kullandığı en popüler sürüm kontrol sistemlerinden biridir. GitHub, GitLab, Bitbucket gibi platformlar üzerinden milyonlarca açık kaynak proje ve ekip çalışması yürütülmektedir.</p>

## Git Nedir?
- Bir bir versiyon kontorl sistemi VCS (Version Control System) yazılımıdır.. Yani, yazılım projelerindeki dosya değişikliklerini takip etmenizi sağlar.
- Git, projenizin geçmişini saklar ve farklı sürümler arasında geçiş yapmanıza imkan tanır.
- Git, bir komut satırı aracı olarak çalışır, yani dosyalarınızı yerel olarak yönetirsiniz. İnternet bağlantısına gerek yoktur, ancak dosyalarınızı paylaşmak isterseniz uzak bir depoya yüklemeniz gerekir.

## Github 
<p align="justify">GitHub versiyon kontrol sistemleri için(örneğin Git) uzak bir depo(repository)dur. Uzak depo demek, bir havuz olarak da düşünülebilir. Birçok yazılımcının bir araya geldiği, bir projenin kopyası üzerinde çalışarak projenin alt sürümlerini çıkardığı ya da çeşitli ihtiyaçlarını giderdiği ve yaptığı değişikliği havuza gönderdiği bir sosyal kodlama alanıdır. </p>

- GitHub, Git’in sunduğu sürüm kontrolü ve işbirliği özelliklerini bulut üzerinde erişilebilir hale getirir. Yazılım projelerinin yönetilmesi, paylaşılması, ekiplerin birlikte çalışması, açık kaynak yazılım geliştirme ve katkı sağlama gibi birçok özelliği içerir. GitHub, günümüzde yazılım dünyasında, açık kaynak geliştiricileri için en önemli araçlardan biri olmuştur.
 
## Github Hesabı Oluşturma

<p align="justify">GitHub üzerinde repository oluşturabilmek için öncelikle bir GitHub hesabınızın olması gerekmektedir. Ücretsiz bir şekilde hesap oluşturabilirsiniz.</p>

[Github Sayfası Linki](https://github.com/) ilgili sayfasından yeni üyelik oluşurabilirsiniz.

## Github'ta Proje Yönetimi
<p align="justify"> GitHub Repository (veya GitHub Deposu), proje dosyalarınızı (kodlar, dökümantasyon, görseller, vb.) barındıran bir alan olup, aynı zamanda Git ile sürüm kontrolü yapmanıza olanak tanır. GitHub depoları, her geliştiricinin projenin farklı sürümleriyle çalışmasına, değişiklikleri takip etmesine, katkıda bulunmasına ve başkalarıyla işbirliği yapmasına imkan verir. </p>
<b>Github repository oluşturmak için aşağıdaki görseldeki işaretli alanlara tıklayabilirsiniz.</b>

![Repository](https://github.com/cyasar34/Git-vs-Github/blob/main/repository_olusturma.jpg)

<b> Yeni repository oluşturma ekranı</b>

![Repository](https://github.com/cyasar34/Git-vs-Github/blob/main/repository_kayit.jpg)

<p align="justify">Üst kısımda repository’inin sahibini ve repo’ya vereceğiniz ismin olduğu alan görülmektedir. Repo’ya isim olarak istediğinizi yazabilirsiniz. Bu alanların altında ise projenin kısa, basit bir açıklamasını yazabileceğiniz alan bulunmaktadır. Açıklama kısmının altında ise projenizin gizli (private) mı yoksa herkes tarafından görülebilir (public) mi olduğunu seçtiğiniz kısım bulunmaktadır. En altta ise README.md dosyası, .gitignore ve license için alanlar bulunmaktadır. Bu alanların seçimi kullanıcıya aittir ama seçmekte fayda bulunmaktadır. Create repository dediğiniz takdirde yeni bir repo oluşturmuş olacaksınız. 
</p>

## GitHub Depolarının (Repository) Özellikleri:
<p align="justify">
 
- **Dosya Yönetimi** : Bir GitHub deposu, tüm proje dosyalarını içerir. Kod dosyaları, belgeler, yapılandırma dosyaları, görseller gibi her şey depoda saklanır.
Depo, bu dosyaların geçmişini tutar. Git ile yapılan her değişiklik, depo içinde kaydedilir, böylece eski sürümlere dönmek ve değişiklikleri incelemek mümkün olur.
- **Sürüm Kontrolü**: GitHub, projede yapılan tüm değişiklikleri takip eder. Git, bir değişiklik yapıldığında, bu değişikliği kaydeder ve her değişikliği bir "commit" olarak adlandırır.
Depodaki commit'ler, bir projenin geçmişine dair bilgi sağlar, böylece hangi dosyalarda ne değişiklik yapıldığını görebiliriz.
- **Branch (Dallanma)**: Bir projede ana kod (master/main branch) üzerinden bağımsız olarak çalışmalar yapılabilmesi için branch (dal) özelliği kullanılabilir. Branch’ler, farklı özelliklerin ya da düzeltmelerin ayrı bir dalda geliştirilmesini sağlar. Ana projeye zarar vermeden yeni özellikler veya düzeltmeler üzerinde çalışılabilir.
- **Pull Requests (PR)**: GitHub, bir dalda yapılan değişikliklerin ana koda entegre edilmesini sağlamak için pull request (PR) özelliğini kullanır. PR, yapılan değişikliklerin diğer ekip üyeleri tarafından gözden geçirilmesini sağlar. Değişiklikler onaylandıktan sonra ana dal ile birleştirilir (merge).
- **Collaborators (Katkıcılar)**: GitHub depoları, başkalarının projeye katkıda bulunmasını sağlamak için collaborators (katkıcılar) özelliğine sahiptir. Projenin sahibi, belirli kişilere erişim izinleri vererek onların projeye katkıda bulunmalarını sağlar. Depo sahibi, katkıcıları yönetebilir ve onlara belirli izinler verebilir (okuma, yazma, yönetici vb.).
- **README Dosyası**: Her GitHub deposunda genellikle bir README.md dosyası bulunur. Bu dosya, projenin açıklamasını, nasıl kullanılacağını ve katkıda bulunma yönergelerini içerir.
Markdown formatında yazılabilir ve projeye dair önemli bilgileri sağlar.
- **Issues (Sorunlar)**: GitHub deposunda issues (sorunlar) kullanılabilir. Bu özellik, hata raporları, geliştirme istekleri ve yapılacak görevleri takip etmek için çok kullanışlıdır.
Her issue, bir görev olarak atanabilir ve tartışma yapılabilir.
- **Actions (Otomasyon ve CI/CD)**: GitHub Actions kullanarak sürekli entegrasyon (CI) ve sürekli dağıtım (CD) süreçlerini otomatikleştirebilirsiniz. Bu sayede, kod değişiklikleri yapıldıkça testler çalıştırılabilir ve dağıtımlar yapılabilir. Örneğin, bir pull request açıldığında otomatik olarak testlerin çalıştırılması sağlanabilir.
- **Wiki ve Belgeler**: GitHub, projeler için bir Wiki alanı sunar. Projeyle ilgili daha fazla bilgi, kılavuzlar ve dökümantasyon burada barındırılabilir.
- **Fork ve Clone**: GitHub, kullanıcıların başka bir kullanıcının deposunu "fork" etmelerine izin verir. Fork, başka bir depo üzerinde bağımsız olarak değişiklik yapmanıza olanak sağlar.
Clone ise bir depoyu kendi bilgisayarınıza indirmenizi sağlar. Bu, yerel olarak proje üzerinde çalışabilmenize imkan tanır.
</p>

## GitHub Depolarının Kullanım Alanları:
- **Açık Kaynak Yazılım Geliştirme**: GitHub, açık kaynak projelerinin geliştirilmesi ve paylaşıldığı en yaygın platformdur.
- **Kişisel veya Kurumsal Projeler**: GitHub depoları, kişisel yazılım projelerinizi veya kurumsal yazılım geliştirme projelerinizi yönetmek için kullanılır.
- **Eğitim ve Öğrenme**: Eğitim materyalleri, örnek kodlar ve kişisel projeler GitHub üzerinde barındırılabilir.
- **Portföyler**: Geliştiriciler, GitHub depolarını portföy olarak kullanabilir, yazdıkları kodları paylaşabilirler.

## Bu Github paylaşımının IEEE ve APA formatlarınada atıf verilme şekli:
- IEEE--> C. Yasar, "Git-vs-Github" GitHub, [Online]. Erişim Linki: https://github.com/cyasar34/Git-vs-Github Son Erişim Tarihi: Gün Ay Yıl.
- APA--> Yasar, C. (2024). Git-vs-Github[GitHub Deposu]. GitHub. Erişim Linki: https://github.com/cyasar34/Git-vs-Github Son Erişim Tarihi: Gün Ay Yıl.
  
> **Proje Durumu:** İlgili dokümanların paylaşımı ders kapsamında gerçekleştirilmiştir. GitHub bölümünden beğeni bildirimi olarak bir yıldız vererek çalışmalarımı destekleyebilirsiniz. <br>
> **Katkıda Bulunma:** Dokümanlarınızda kullanılacaksanız ilgili atıf yöntemlerini kullanmanız ve haber vermeniz çok önemlidir. <br>
> **Lisans:** MIT Lisansı altında yayımlandı.  

License:
This work is licensed under a Creative Commons Attribution-Non Commercial 4.0 International License, allowing non-commercial sharing and adaptation with proper attribution.
