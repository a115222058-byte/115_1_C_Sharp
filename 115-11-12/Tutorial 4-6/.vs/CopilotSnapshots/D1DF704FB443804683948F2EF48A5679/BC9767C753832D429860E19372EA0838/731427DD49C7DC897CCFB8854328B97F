using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Time_Zone
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
            ConfigureInterface();
        }

        private void ConfigureInterface()
        {
            Font interfaceFont = new Font("Microsoft JhengHei UI", 18F);

            this.Font = interfaceFont;
            this.Text = "時區";
            this.ClientSize = new Size(620, 520);
            this.StartPosition = FormStartPosition.CenterScreen;

            this.promptLabel.AutoSize = false;
            this.promptLabel.Font = interfaceFont;
            this.promptLabel.Location = new Point(30, 25);
            this.promptLabel.Size = new Size(560, 70);
            this.promptLabel.Text = "選擇城市，我會告訴您該城市的時區。";
            this.promptLabel.TextAlign = ContentAlignment.MiddleLeft;

            this.cityListBox.Font = interfaceFont;
            this.cityListBox.Location = new Point(30, 115);
            this.cityListBox.Size = new Size(560, 175);
            this.cityListBox.ItemHeight = 36;
            this.cityListBox.Items.Clear();
            this.cityListBox.Items.AddRange(new object[]
            {
                "丹佛",
                "檀香山",
                "明尼阿波利斯",
                "紐約",
                "舊金山"
            });

            this.outputDescriptionLabel.AutoSize = false;
            this.outputDescriptionLabel.Font = interfaceFont;
            this.outputDescriptionLabel.Location = new Point(30, 325);
            this.outputDescriptionLabel.Size = new Size(150, 45);
            this.outputDescriptionLabel.Text = "時區：";
            this.outputDescriptionLabel.TextAlign = ContentAlignment.MiddleLeft;

            this.timeZoneLabel.Font = interfaceFont;
            this.timeZoneLabel.Location = new Point(190, 325);
            this.timeZoneLabel.Size = new Size(400, 50);
            this.timeZoneLabel.Text = "";
            this.timeZoneLabel.TextAlign = ContentAlignment.MiddleCenter;

            this.okButton.Font = interfaceFont;
            this.okButton.Location = new Point(155, 425);
            this.okButton.Size = new Size(140, 55);
            this.okButton.Text = "確定";

            this.exitButton.Font = interfaceFont;
            this.exitButton.Location = new Point(325, 425);
            this.exitButton.Size = new Size(140, 55);
            this.exitButton.Text = "離開";
        }

        private void okButton_Click(object sender, EventArgs e)
        {
        }

        private void exitButton_Click(object sender, EventArgs e)
        {
            // 關閉表單。
            this.Close();
        }
    }
}