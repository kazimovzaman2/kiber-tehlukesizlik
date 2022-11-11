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
HTML ilə yazdığınız CV-niz;

AWS üçün: <a href="https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html">Amazon S3 static website</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website">Azure Storage static site</a>

GCP üçün: <a href="https://cloud.google.com/storage/docs/hosting-static-website">Google Cloud Storage</a>

üzərində işləməlidir. Əslində bunun üçün Netlify və Github Pages-dən istifadə daha yaxşı ola bilər. Amma hazırda cloud bildiyimizi göstərməyə çalışmalıyıq. Ona görə yuxarıdakı xidmətlərdən birini istifadə etməliyik.
<br><br><br><br>



## HTTPS
CV vebsaytının təhlükəsizliyi üçün HTTPS-dən istifadə etməliyik.

AWS üçün: <a href="https://aws.amazon.com/blogs/networking-and-content-delivery/amazon-s3-amazon-cloudfront-a-match-made-in-the-cloud/">Amazon CloudFront</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/storage-custom-domain-name?tabs=azure-portal#map-a-custom-domain-with-https-enabled">Azure CDN</a>

GCP üçün: <a href="https://cloud.google.com/load-balancing/docs/https">Cloud CDN</a>

xidmətlərindən birini istifadə etməli olacaqsınız.
<br><br><br><br>




## DNS
Özünüzə bir domain alın. 

AWS üçün: <a href="https://aws.amazon.com/route53/">Amazon Route53</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/azure/cdn/cdn-map-content-to-custom-domain">Azure DNS</a>

GCP üçün: <a href="https://cloud.google.com/domains/docs">Cloud Domains</a>

və ya bundan əlavə hərhansı bir DNS provayderi istifadə edə bilərsiz. Domain almaq ortalama 10 dolar olur.
<br><br><br><br>




## Javascript
CV səhifənizdə ziyarətçi sayğacı olmalıdır. Bunun üçün biraz Javascript yazmalısınız. <a href="https://www.codecademy.com/learn/introduction-to-javascript">Bu saytdan javascriptə başlayabilərsiniz.</a>
<br><br><br><br>




## Verilənlər bazası
Ziyarətçilərin sayını göstərə və yeniləyə bilmək üçün verilənlər bazasından istifadə etməlisiniz. 

AWS üçün: <a href="https://aws.amazon.com/dynamodb/">DynamoDB</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/azure/cosmos-db/introduction">CosmosDB</a>-dən <a href="https://docs.microsoft.com/en-us/azure/cosmos-db/table/introduction">Table API</a>

GCP üçün: <a href="https://cloud.google.com/firestore">Firestore</a>

xidmətlərindən istifadə etməyi məsləhət görürəm.
<br><br><br><br>




## API
Birbaşa javascript üzərinden verilənlər bazası ilə əlaqə saxlamayın. Bunun əvəzinə veb tətbiqinizdən gələn sorğuları qəbul edən və verilənlər bazanızla əlaqə saxlayan API yaradın. Bunun üçün istifadə etdiyiniz bulud xidmətinin API Gateway və Lambda xidmətlərindən istifadə edin. Bu xidmətlər bizim əməliyyatlarımız üçün ya pulsuz, ya da çox ucuz olacaq.
<br><br><br><br>




## Python
Lambda funksiyası üçün biraz kod yazmalı olacaqsıznız; daha çox Javascript istifadə edə bilərsiniz, lakin hazırkı məqsədimiz üçün Python və bulud xidmətinin təqdim etdiyi kitabxanaları bir az araşdırmaq daha yaxşı olardı.

AWS üçün: <a href="https://boto3.amazonaws.com/v1/documentation/api/latest/index.html">boto3</a>

AZURE üçün: <a href="https://github.com/Azure/azure-sdk-for-python">Azure SDK</a>

GCP üçün: <a href="https://cloud.google.com/python/docs/reference">Google Cloud Client Libraries</a>

<br><br><br><br>




## Testlər
Python kodunuza bəzi testlər əlavə etməlisiniz. Burada yaxşı python testləri yazmaq üçün <a href="https://realpython.com/python-testing/">mənbə</a> qoyuram.
<br><br><br><br>




## Infrastracture as Code

API resurslarınızı -DynamoDB, CosmosDB, GoogleFunctions- əl ilə harasa klikləməklə təyin etməməlisiniz. Bunun yerine onları;

AWS üçün: <a href="https://aws.amazon.com/serverless/sam/">AWS Serversiz Tətbiq Modeli (SAM) şablonunda</a>

AZURE üçün: <a href="https://docs.microsoft.com/en-us/azure/azure-functions/functions-infrastructure-as-code">Azure Resource Manager (ARM) şablonunda</a>

GCP üçün: <a href="https://cloud.google.com/blog/topics/developers-practitioners/predictable-serverless-deployments-terraform">Terraform şablonunda</a>

müəyyən edin və bulud xidməti tərəfindən təmin edilən CLI-dən istifadə edərək yerləşdirin. Bu, Kod kimi İnfrastruktur və ya qısaca IaC kimi tanınır və uzunmüddətli layihələrdə vaxtınıza qənaət edir.
<br><br><br><br>




## Mənbə Nəzarəti
Hər dəfə backend API-ni və ya saytınızın frontend kodunu dəyişdirdiyiniz zaman əl ilə yenidən yerləşdirmək istəməzsiniz. Kodunuza etdiyiniz hər dəyişikliklə onun avtomatik yenilənməsini istəyərsiniz. (Bu <a href="https://help.github.com/en/actions/building-and-testing-code-with-continuous-integration/about-continuous-integration">davamlı inteqrasiya və deployment</a> yəni qısaca CI/CD olaraq bilinir)
<br><br><br><br>




## CI/CD (Backend)
Github Actions'ı Serverless Application Model template və ya python kodunuzu güncəlləmək üçün təyin edin, siz kodunuzu güncəllədiyinizde Python testləri işləyəcək. Testdən keçərsə, Tətbiqiniz paketlənəcək və bulud xidmətinin təqdim etdiyi proqramda dərc olunacaq.
<br><br><br><br>




## CI/CD (Frontend)
Frontend kodu üçün başqa Github repo açın və bu repo üçün də Github Actions təyin edin, dəyişiklik bulud xidməti ilə təmin edilən proqramda avtomatik yenilənəcək. Vacib qeyd: HEÇ VAXT etimadnamənizi mənbə nəzarətinə əlavə etməyin! Pis fikirli insanlar bu məlumatı sizə qarşı istifadə edə bilər.
<br><br><br><br>




## Blog Post
Nəhayət, bloq yazısı aça və bu layihə üzərində işləyərkən öyrəndiklərinizi yazıb CV-yə daxil edə bilərsiniz. Eğer kendi blogunuz yoksa bu yazıyı  Öz bloqunuz yoxdursa, bu məqaləni <a href="https://dev.to">Dev.to</a> saytında dərc edə bilərsiniz.
<br><br><br><br>




## Daha çox məlumat üçün
Stratejiler, araçlar ve sizin cloud alanında iş bulmanızı sağlayabilecek daha fazla challenge için <a href="https://forrestbrazeal.gumroad.com/l/cloud-resume-challenge-book">the Cloud Resume Challenge book</a>'a bakabilirsiniz.
Sizi buludda iş əldə edə biləcək strategiyalar, alətlər və daha çox çağırışlar üçün <a href="https://forrestbrazeal.gumroad.com/l/cloud-resume-challenge-book">the Cloud Resume Challenge book</a>-a baxın.
<br><br><br><br>




## Orijinal Kaynak
[Kaynak](https://github.com/LuNiZz/siber-guvenlik-sss/blob/master/Belgeler/Dokumanlar/CV_Challenge.md)
