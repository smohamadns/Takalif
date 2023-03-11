using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;
using System.Net.Mail;
using System.Net;

namespace WindowsFormsApp2
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            try
            {
                MailMessage mail = new MailMessage();
                SmtpClient SmtpServer = new SmtpClient("smtp.gmail.com");
                mail.From = new MailAddress("smns.1381@gmail.com");

                mail.To.Add("mohamadns2002@gmail.com");
                mail.Subject = "slm";
                mail.Body = "هزار تا سلام";

                SmtpServer.Port = 587;
                SmtpServer.Credentials = new System.Net.NetworkCredential("Mohamad Nouri", "smns2717");
                SmtpServer.EnableSsl = true;

                SmtpServer.Send(mail);
                MessageBox.Show("mail Send");
            }
            catch (Exception ex)

            {
                MessageBox.Show(ex.ToString());
            }



        }
    }
}
