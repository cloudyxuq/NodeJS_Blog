
package com.lume;

import org.apache.commons.mail.DefaultAuthenticator;
import org.apache.commons.mail.Email;
import org.apache.commons.mail.MultiPartEmail;

/**
 * 
 */

/**
 * @author Administrator
 */
public class SendEmail
{
    public static boolean sendEmail(EmailBean bean) throws Exception
    {
        /**
         * https://javamail.java.net/docs/SSLNOTES.txt
         */
        System.setProperty("mail.smtp.ssl.enable" , "");
        System.setProperty("mail.smtp.ssl.socketFactory.class" , "");
        System.setProperty("mail.smtp.ssl.socketFactory.fallback" , "");
        Email email = new MultiPartEmail();
        email.setHostName(bean.getHostName());
        email.setSmtpPort(bean.getSmtpPort());
        email.setAuthenticator(new DefaultAuthenticator(bean.getAuthName(),
                bean.getAuthPwd()));
        if ( bean.getIsSSL() )
        {
            email.setSSLOnConnect(Boolean.TRUE);
            email.setSslSmtpPort(bean.getSmtpSSLProt());
            System.setProperty("mail.smtp.ssl.enable" , "true");
            System.setProperty("mail.smtp.ssl.socketFactory.class" ,
                    "com.lume.DummySSLSocketFactory");
            System.setProperty("mail.smtp.ssl.socketFactory.fallback" , "false");
        }
        email.setFrom(bean.getSendFrom());
        email.setSubject(bean.getTitle());
        email.setMsg(bean.getContent());
        email.addTo(bean.getAddTo());

        email.setDebug(true);

        email.send();

        return true;
    }

    public static void main(String[] args)
    {
        try
        {
            EmailBean bean = getGoogleBean();
            // bean = getMdeamonBean();
            System.out.println(sendEmail(bean));
        } catch ( Exception e )
        {
            // TODO Auto-generated catch block
            e.printStackTrace();
        }
    }

    private static EmailBean getMdeamonBean()
    {
        EmailBean bean = new EmailBean();
        bean.setHostName("192.168.1.100");
        bean.setSmtpPort(25);
        bean.setSmtpSSLProt("465");
        bean.setAuthName("xuqiang@xq.com");
        bean.setAuthPwd("Admin@123");
        bean.setIsSSL(Boolean.TRUE);
        bean.setTitle("THis Mdeamon SSL");
        bean.setContent("HHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHH");
        bean.setSendFrom("xuqiang@xq.com");
        bean.setAddTo("xuqiang@xq.com");
        return bean;
    }

    private static EmailBean getGoogleBean()
    {
        EmailBean bean = new EmailBean();
        bean.setHostName("smtp.googlemail.com");
        bean.setSmtpPort(465);
        bean.setSmtpSSLProt("465");
        bean.setAuthName("xxx@gmail.com");
        bean.setAuthPwd("");
        bean.setIsSSL(Boolean.TRUE);
        bean.setTitle("THis Google SSL");
        bean.setContent("!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!");
        bean.setSendFrom("cloudyxuq@gmail.com");
        bean.setAddTo("cloudyxuq@gmail.com");
        return bean;

    }

}
