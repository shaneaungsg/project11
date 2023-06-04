Step1: Install xamp at C:\xampp

Step2: Install Composer-Setup.exe 2a)use c:\xamp\php\php.exe 2b)add to path

Step3:Download projecct11.zip public.zip vendor.zip  at github 
3a)unzip project11 then unzip public and vendor folder 
3b)and move public and vendor folders into project11 folder

Step4:Run xampp Control Panel

Step5:At xampp 5a)Start apache and 5b)Start mysql

Step6:Open project11path at terminal

Step7: C:\Users\Shane\Desktop\project11>php artisan migrate 7a)create project11 -> yes

Step8:C:\Users\Shane\Desktop\project11>php artisan db:seed

Step9:C:\Users\Shane\Desktop\project11>php artisan serve

Step10:At chrome http://127.0.0.1:8000/admin/login

user name: admin@admin.com password: 123456
