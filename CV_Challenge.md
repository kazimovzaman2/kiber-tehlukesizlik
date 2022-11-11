<a name="top"></a>
<h1 align="center">CV Challenge</h1>

## Sertifikat
CV-nizdə;

AWS üçün: <a href="https://aws.amazon.com/certification/certified-cloud-practitioner/">AWS Cloud Practitioner</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/learn/certifications/exams/az-900">AZ-900</a>

GCP üçün: <a href="https://cloud.google.com/certification/cloud-digital-leader">Google Cloud Digital Leader</a> 

sertifikatı olmalıdır. Bu sertifikatlar giriş səviyyəli bulud sertifikatlarıdır. Bundan daha iləri səviyyə sertifikatınız varsa da mümkündür. Bu imtahanların hər birini 100 dollara onlayn olaraq verə bilərsiniz.
<br><br><br><br>




## HTML
CV-niz <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a> ilə hazırlanmalıdır. (Word, pdf olarak yox)
<br><br><br><br>




## CSS
CV-nizi hazırlayarkən <a href="https://www.w3schools.com/css/">CSS</a> ilə formalaşdırmaq lazımdır. Dizayn zövqünüz olmamağı, önəm kəsb etmir. Çox gözəl dizayna ehtiyac yoxdur. Ancaq veb səhifəni açarkən sırf HTML-dən başqa bir şey görməliyik.
<br><br><br><br>




## Statik veb sayt
HTML ile yazdığınız CV-niz;

AWS üçün: <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html">Amazon S3 static website</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website">Azure Storage static site</a>

GCP üçün: <a href="https://cloud.google.com/storage/docs/hosting-static-website">Google Cloud Storage</a>

üzerinde işləməlidir. Əslində bunun için Netlify ve Github Pages-dən istifadə daha yaxşı ola bilər. Amma hazırda cloud bildiyimizi göstərməyə çalışmalıyıq. Ona görə yuxardakı xidmətlərindən birini istifadə etməliyik.
<br><br><br><br>



## HTTPS
CV vebsaytının təhlükəsizliyi üçün HTTPS-dən istifadə etməliyik.

AWS üçin: <a href="https://aws.amazon.com/blogs/networking-and-content-delivery/amazon-s3-amazon-cloudfront-a-match-made-in-the-cloud/">Amazon CloudFront</a>

AZURE üçin: <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/storage-custom-domain-name?tabs=azure-portal#map-a-custom-domain-with-https-enabled">Azure CDN</a>

GCP üçin: <a href="https://cloud.google.com/load-balancing/docs/https">Cloud CDN</a>

xidmətlərindən birini istifadə etməli olacaqsınız.
<br><br><br><br>




## DNS
Kendinize bir domain (alan adı) alın. 

AWS için: <a href="https://aws.amazon.com/route53/">Amazon Route53</a>

AZURE için: <a href="https://docs.microsoft.com/en-us/azure/cdn/cdn-map-content-to-custom-domain">Azure DNS</a>

GCP için: <a href="https://cloud.google.com/domains/docs">Cloud Domains</a>

veya bunlar dışında herhangi bir DNS sağlayıcıyı kullanabilirsiniz. Domain almak genelde 10 dolar civarı oluyor.
<br><br><br><br>




## Javascript
Özgeçmiş sayfanızın bir ziyaretçi sayacı olmalı. Bunu gerçekleştirebilmek için biraz Javascript yazmanız gerekiyor. <a href="https://www.codecademy.com/learn/introduction-to-javascript">Bu siteden javascripte başlayabilirsiniz.</a>
<br><br><br><br>




## Veritabanı
Ziyaretçi sayısını gösterebilmeniz ve güncelleyebilmeniz için bir veritabanı kullanmalısınız. 

AWS için: <a href="https://aws.amazon.com/dynamodb/">DynamoDB</a>

AZURE için: <a href="https://docs.microsoft.com/en-us/azure/cosmos-db/introduction">CosmosDB</a>'den <a href="https://docs.microsoft.com/en-us/azure/cosmos-db/table/introduction">Table API</a>

GCP için: <a href="https://cloud.google.com/firestore">Firestore</a>

servislerini kullanmanızı öneririm. (Veritabanı için istek-üzerine (on-demand) fiyatlandırma seçerseniz ve veritabanınızda kullanmanız gerekenden daha fazla veri saklamazsanız veya göstermezseniz neredeyse hiç para ödemeden kullanacanksınız.)
<br><br><br><br>




## API
Direk javascript üzerinden veritabanı ile iletişim kurmayın. Bunun yerine web uygulamanızdan gelen istekleri kabul eden ve veritabanınız ile iletişime geçen bir API yaratın. Bunun için kullandığınız bulut servisinin API Geçidini ve Lambda servislerini kullanın. Yaptığımız işlemler için bu servisler ya ücretsiz ya da çok ucuz olacaktır.
<br><br><br><br>




## Python
Lambda fonksiyonu için biraz kod yazmanız gerekecek; daha fazla Javascript kullanabilirsiniz ancak şu anki amacımız için Python'u ve bulut servisinin sağladığı kütüphaneleri biraz keşfetmek daha iyi olacaktır.

AWS için: <a href="https://boto3.amazonaws.com/v1/documentation/api/latest/index.html">boto3</a>

AZURE için: <a href="https://github.com/Azure/azure-sdk-for-python">Azure SDK</a>

GCP için: <a href="https://cloud.google.com/python/docs/reference">Google Cloud Client Libraries</a>

Buraya ucuz ve ücretsiz bir <a href="https://www.learnpython.org/">Python kursu</a> bırakıyorum. Diğer kaynaklar için [sss.lunizz.com](https://sss.lunizz.com) adresini ziyaret edebilirsiniz.
<br><br><br><br>




## Testler
Python kodunuza bazı testler eklemelisiniz. Buraya iyi python testleri yazmak için bir <a href="https://realpython.com/python-testing/">kaynak</a> bırakıyorum.
<br><br><br><br>




## Altyapı olarak kod (Infrastracture as Code)

API kaynaklarınızı -DynamoDB, CosmosDB, GoogleFunctions- elle bir yerlere tıklayarak ayarlamamalısınız. Bunun yerine onları;

AWS için: <a href="https://aws.amazon.com/serverless/sam/">AWS Sunucusuz Uygulama Modeli (SAM) şablonunda</a>

AZURE için: <a href="https://docs.microsoft.com/en-us/azure/azure-functions/functions-infrastructure-as-code">Azure Resource Manager (ARM) şablonunda</a>

GCP için: <a href="https://cloud.google.com/blog/topics/developers-practitioners/predictable-serverless-deployments-terraform">Terraform şablonunda</a>

belirleyin ve bulut servisinin sağladığı CLI'yi kullanarak deploy edin. Bu Infstatructure as Code veya kısaca IaC olarak geçer ve uzun zamanlı projelerde size zaman kazandırır.
<br><br><br><br>




## Kaynak Kontrolü
Backend API'ınızı veya sitenizin frontend kodunu her değiştirdiğinizde tekrar elle deploy etmek istemezsiniz. Kodunuza yaptığınız her değişiklikte otomatik olarak güncellenmesini istersiniz. (Bu <a href="https://help.github.com/en/actions/building-and-testing-code-with-continuous-integration/about-continuous-integration">devamlı integrasyon ve deployment</a> yani kısaca CI/CD olarak geçer)
<br><br><br><br>




## CI/CD (Backend)
Github Actions'u Serverless Application Model template veya python kodunuzu güncellemek için ayarlayın, siz kodunuzu güncellediğinizde Python testleriniz çalışacak. Eğer testten geçerse, Uygulamanız paketlenecek ve bulut servisinin sağladığı uygulama üzerinde yayınlanacak.
<br><br><br><br>




## CI/CD (Frontend)
Frontend kodu için bir Github reposu daha açın ve bu repo için de bir Github Actions ayarlayın, Değişiklik bulut servisinin sağladığı uygulama üzerinde otomatik olarak güncellenecek. Önemli Not: ASLA kimlik bilgilerinizi kaynak kontrolüne eklemeyin! Art niyetki kişiler bu bilgileri size karşı kullanabilir.
<br><br><br><br>




## Blog Post
Son olarak, bir blog yazısı açıp bu proje üstünde çalışırken öğrendiğiniz şeyleri yazıp özgeçmişinizin içine ekleyebilirsiniz. Eğer kendi blogunuz yoksa bu yazıyı <a href="https://dev.to">Dev.to</a> üzerinden yayınlayabilirsiniz.
<br><br><br><br>




## Daha fazlası için
Stratejiler, araçlar ve sizin cloud alanında iş bulmanızı sağlayabilecek daha fazla challenge için <a href="https://forrestbrazeal.gumroad.com/l/cloud-resume-challenge-book">the Cloud Resume Challenge book</a>'a bakabilirsiniz.
<br><br><br><br>




## Orijinal Kaynak
[Kaynak](https://cloudresumechallenge.dev/docs/the-challenge/)