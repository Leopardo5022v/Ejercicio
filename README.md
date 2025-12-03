# Ejercicio
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            int edad1 = int.Parse(txtEdad1.Text);
            int edad2 = int.Parse(txtEdad2.Text);

            if (edad1 > edad2)
            {
                int dif = edad1 - edad2;
                MessageBox.Show("La primera persona es mayor por " + dif + " años.");
            }
            else if (edad2 > edad1)
            {
                int dif = edad2 - edad1;
                MessageBox.Show("La segunda persona es mayor por " + dif + " años.");
            }
            else
            {
                MessageBox.Show("Ambas personas tienen la misma edad.");
            }
        }

        private void label3_Click(object sender, EventArgs e)
        {

        }
    }
}
