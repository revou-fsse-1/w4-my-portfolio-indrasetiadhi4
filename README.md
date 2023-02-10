# Deploy a Website on Netlify & Setup Custom Domain

> Assignment for RevoU - FSSE week 4

## Deployment on Netlify

1. Go to https://www.netlify.com, click **Sign up** or **Log in** if you already have an account.

   ![Netlify](assets/netlify.jpg)

2. Log in with one of the following acccount.

   ![Sign Up](assets/sign-up.jpg)

3. Go to **Sites** page, and then click **Add new site**

   ![Add New Site](assets/add-new-site.jpg)

4. Choose **Import an existing project** and **GitHub** if you already have a repository you want to deploy.

   ![Import Project](assets/import-an-existing-project.jpg)

   ![Github](assets/github.jpg)

5. Select a repository that you want to deploy.

   ![Repo](assets/select-repository.jpg)

6. Configure the settings and click **Deploy site**

   ![Deploy](assets/deploy-site.jpg)

7. Your website has been deployed with the URL given by netlify.

   ![Website's URL](assets/url-netlify.jpg)

8. If you want to customize your domain, open **Site settings** and click **Change site name**.

   ![Change Site Name](assets/change-site-name.jpg)

9. Enter with your desired name, then click **Save**.

   ![Enter Site Name](assets/enter-site-name.jpg)

10. Your website has been deployed.

## Buy a Custom Domain on Niagahoster

1. Go to https://www.niagahoster.co.id, then **Log in** with your account.

   ![Niagahoster](assets/niagahoster.jpg)

2. Choose **Domain** and click **Order sekarang** for buying a domain.

   ![Order Domain](assets/order-domain.jpg)

3. Fill your desired name, then choose one available domain. After that, click **Pilih** for the next process.

   ![Select Domain](assets/select-domain.jpg)

4. Check your domain, then click **Lanjutkan** for the payment process.

   ![Payment](assets/niagahoster-payment.jpg)

5. After you complete your payment, you can use your domain.

## Connect Website to Domain and DNS

1. Go to https://www.cloudflare.com, then **Log in** with your account.

   ![Cloudflare](assets/cloudflare.jpg)

2. Click **Add site** on navigation bar. Fill your domain, then click **Add site** button.

   ![Add Site](assets/add-site.jpg)

3. For this project, we will choose **free plan**, then click **continue**.

   ![Domain Plan](assets/domain-plan.jpg)

4. Click **Add record** for manage the DNS.

   ![Add Record](assets/add-record.jpg)

5. Choose **CNAME** as the **type**, fill your new domain in **Name** and fill your netlify's domain in **Target**. Then, click **Continue**.

   ![DNS](assets/cloudflare-dns.jpg)

   ![continue](assets/cloudflare-continue.jpg)

6. Go to https://client.niagahoster.co.id, click **layanan** on navigation bar, then choose **Layanan Saya**. Find your domain, then click **Kelola Layanan**.

   ![layanan](assets/niagahoster-layanan.jpg)

7. Click **Ubah Nameserver**, fill the nameserver that provided by the cloudflare.

   ![nameserver](assets/niagahoster-nameserver.jpg)
   ![nameserver](assets/niagahoster-update-nameserver.jpg)

8. Back to netlify, then choose **Set up a custom domain**.

   ![Custom Domain](assets/custom-domain-netlify.jpg)

9. Fill your new domain.

   ![New Domain](assets/new-domain.jpg)

10. Done! Your website can be accessed by your new domain.
