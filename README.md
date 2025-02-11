# Git vs Github

## Git Tarihçesi
<p align="justify">2005 yılı öncesinde Linux işletim sistemi çekirdeği, kapalı kaynak kodlu olan BitKeeper sistemi üzerinde geliştirilmekteydi. BitKeeper’ın sahibi olan firmanın, Linux geliştiricilerine tanımış olduğu ücretsiz kullanım iznini iptal etmesi üzerine Linus Torvalds ve diğer çekirdek geliştiricileri kendi sürüm kontrol sistemlerini geliştirmeye başlarlar. Bu yeni sürüm kontrol sistemi Git adını alır.</p>
<p align="justify">Git, günümüzde dünya çapında yazılım geliştiricilerinin kullandığı en popüler sürüm kontrol sistemlerinden biridir. GitHub, GitLab, Bitbucket gibi platformlar üzerinden milyonlarca açık kaynak proje ve ekip çalışması yürütülmektedir.</p>

## Git Nedir?
- Bir bir versiyon kontrol sistemi VCS (Version Control System) yazılımıdır. Yani, yazılım projelerindeki dosya değişikliklerini takip etmenizi sağlar.
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


# Git vs Github

## Git History
<p align="justify">Prior to 2005, the Linux operating system kernel was developed on the closed source BitKeeper system. After the company that owned BitKeeper revoked the free license it had granted to Linux developers, Linus Torvalds and other kernel developers started to develop their own version control system. This new version control system was called Git.</p>
<p align="justify">Git is one of the most popular version control systems used by software developers around the world today. Millions of open source projects and teamwork are carried out on platforms such as GitHub, GitLab and Bitbucket.</p>

## What is Git?
- A version control system is VCS (Version Control System) software. That is, it allows you to keep track of file changes in software projects.
- Git stores the history of your project and allows you to switch between different versions.
- Git works as a command line tool, meaning you manage your files locally. You don't need an internet connection, but if you want to share your files, you need to upload them to a remote repository.

## Github 
<p align="justify">GitHub is a remote repository for version control systems (e.g. Git). A remote repository can also be thought of as a repository. It is a social coding space where many developers come together, work on a copy of a project, release sub-versions of the project or address various needs, and submit their changes to the repository. </p>

- GitHub makes Git's version control and collaboration features accessible on the cloud. It includes many features such as managing and sharing software projects, teams working together, open source software development and contribution. GitHub has become one of the most important tools for open source developers in the software world today.
 
## Creating a Github Account

<p align="justify">In order to create a repository on GitHub, you must first have a GitHub account. You can create an account for free.</p>

[Github Sayfası Linki](https://github.com/) you can create a new membership from the relevant page.

## Project Management on Github
<p align="justify"> A GitHub Repository (or GitHub Repository) is a space that hosts your project files (code, documentation, images, etc.) and also allows you to perform version control with Git. GitHub repositories allow each developer to work with different versions of the project, track changes, contribute, and collaborate with others. </p>
<b>You can click on the marked fields in the image below to create a Github repository.</b>

![Repository](https://github.com/cyasar34/Git-vs-Github/blob/main/repository_olusturma.jpg)

<b> New repository creation screen</b>

![Repository](https://github.com/cyasar34/Git-vs-Github/blob/main/repository_kayit.jpg)

<p align="justify">At the top you can see the owner of the repository and the name of the repo. You can name the repo anything you want. Below these fields is a field where you can write a short, simple description of the project. Below the description, you can choose whether your project is private or public. At the bottom there are fields for README.md file, .gitignore and license. The choice of these fields is up to the user, but it is useful to select them. If you say Create repository, you will create a new repo. 
</p>

## Features of GitHub Repositories:
<p align="justify">
 
- **File Management** : A GitHub repository contains all project files. Everything from code files, documentation, configuration files, images, etc. are stored in the repository.
The repository keeps a history of these files. Every change made with Git is saved in the repository, so it is possible to go back to older versions and review the changes.
- **Version Control**: GitHub keeps track of all changes made to the project. When a change is made, Git saves that change and calls each change a “commit”.
The commits in the repository provide information about the history of a project, so we can see which files have been modified and what changes were made.
- **Branch: The branch feature can be used to work on a project independently from the main code (master/main branch). Branches allow different features or fixes to be developed in a separate branch. New features or fixes can be worked on without damaging the main project.
- **Pull Requests (PR)**: GitHub uses pull requests (PR) to ensure that changes made in a branch are integrated into the main code. PR allows the changes to be reviewed by other team members. Once the changes are approved, they are merged with the main branch (merge).
- **Collaborators**: GitHub repositories have a collaborators feature to enable others to contribute to the project. The owner of the project allows certain people to contribute to the project by granting them access permissions. The repository owner can manage contributors and grant them certain permissions (read, write, admin, etc.).
- **README File**: Every GitHub repository usually has a README.md file. This file contains a description of the project, how to use it, and guidelines for contributing.
It can be written in Markdown format and provides important information about the project.
- **Issues**: Issues are available in the GitHub repository. This feature is very useful for tracking bug reports, development requests and tasks to be done.
Each issue can be assigned as a task and can be discussed.
- **Actions (Automation and CI/CD)**: You can automate continuous integration (CI) and continuous deployment (CD) processes using GitHub Actions. This way, tests can be run and deployments can be made as code changes are made. For example, tests can be run automatically when a pull request is opened.
- **Wiki and Documentation**: GitHub provides a Wiki area for projects. More information, guides and documentation about the project can be hosted here.
- **Fork and Clone**: GitHub allows users to “fork” another user's repository. A fork allows you to independently make changes to another repository.
Clone allows you to download a repository to your own computer. This allows you to work on the project locally.
</p>

## GitHub Repositories Use Cases:
- **Open Source Software Development**: GitHub is the most common platform for developing and sharing open source projects.
- **Personal or Enterprise Projects**: GitHub repositories are used to manage your personal software projects or enterprise software development projects.
- **Training and Learning**: Training materials, sample code and personal projects can be hosted on GitHub.
- **Portfolios**: Developers can use GitHub repositories as portfolios and share their code.

## This is how this Github post is cited in IEEE and APA formats:
- IEEE--> C. Yasar, "Git-vs-Github" GitHub, [Online]. Access Link: https://github.com/cyasar34/Git-vs-Github Date Last Accessed: Day Month Year.
- APA--> Yasar, C. (2024). Git-vs-Github[GitHub Deposu]. GitHub. Access Link: https://github.com/cyasar34/Git-vs-Github Date Last Accessed: Day Month Year.
  
> **Project Status:** The sharing of the relevant documents was realized within the scope of the course. GitHub bölümünden beğeni bildirimi olarak bir yıldız vererek çalışmalarımı destekleyebilirsiniz. <br>
> **Contribution:** It is very important that you use the relevant citation methods and notify us if you will be used in your documents. <br>
> **License:** Released under the MIT License.

License:
This work is licensed under a Creative Commons Attribution-Non Commercial 4.0 International License, allowing non-commercial sharing and adaptation with proper attribution.
