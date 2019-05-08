1. Crear tres repositorios en GitHub con el nombre “Interfaz Grafica de Usuario - Calculadora”, “Interfaz Grafica de Usuario – Tres en Raya” y “Interfaz Grafica de Usuario – El Ahorcado”
![1 1](https://user-images.githubusercontent.com/49033575/57344674-bf545780-710d-11e9-8551-8248730c43d9.png)

2.
![1 2](https://user-images.githubusercontent.com/49033575/57344767-27a33900-710e-11e9-8397-6fab5aa2eb67.png)
 
package ec.edu.ups.vista;

public class VentanaPrincipal extends javax.swing.JFrame {

    String a;
    String p;
    int c;
    double x;
    int cn;
    int y;

    public VentanaPrincipal() {
        initComponents();
        p = "";
        cn = 0;
    }

   
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        txtPantalla = new javax.swing.JTextField();
        btn7 = new javax.swing.JButton();
        btn4 = new javax.swing.JButton();
        btn1 = new javax.swing.JButton();
        btn8 = new javax.swing.JButton();
        btn5 = new javax.swing.JButton();
        btn2 = new javax.swing.JButton();
        jButton8 = new javax.swing.JButton();
        btn9 = new javax.swing.JButton();
        btn6 = new javax.swing.JButton();
        btn3 = new javax.swing.JButton();
        jButton12 = new javax.swing.JButton();
        jButton13 = new javax.swing.JButton();
        jButton14 = new javax.swing.JButton();
        jButton15 = new javax.swing.JButton();
        jButton16 = new javax.swing.JButton();
        jButton17 = new javax.swing.JButton();
        jButton18 = new javax.swing.JButton();
        jButton19 = new javax.swing.JButton();
        jButton20 = new javax.swing.JButton();
        jButton21 = new javax.swing.JButton();
        jButton22 = new javax.swing.JButton();
        jButton23 = new javax.swing.JButton();
        jButton24 = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        txtPantalla.setText("0");
        txtPantalla.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                txtPantallaActionPerformed(evt);
            }
        });

        btn7.setText("7");
        btn7.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn7ActionPerformed(evt);
            }
        });

        btn4.setText("4");
        btn4.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn4ActionPerformed(evt);
            }
        });

        btn1.setText("1");
        btn1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn1ActionPerformed(evt);
            }
        });

        btn8.setText("8");
        btn8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn8ActionPerformed(evt);
            }
        });

        btn5.setText("5");
        btn5.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn5ActionPerformed(evt);
            }
        });

        btn2.setText("2");
        btn2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn2ActionPerformed(evt);
            }
        });

        jButton8.setText("0");
        jButton8.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton8ActionPerformed(evt);
            }
        });

        btn9.setText("9");
        btn9.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn9ActionPerformed(evt);
            }
        });

        btn6.setText("6");
        btn6.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn6ActionPerformed(evt);
            }
        });

        btn3.setText("3");
        btn3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btn3ActionPerformed(evt);
            }
        });

        jButton12.setText(",");

        jButton13.setText("+");
        jButton13.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton13ActionPerformed(evt);
            }
        });

        jButton14.setText("-");
        jButton14.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton14ActionPerformed(evt);
            }
        });

        jButton15.setText("/");
        jButton15.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton15ActionPerformed(evt);
            }
        });

        jButton16.setText("*");
        jButton16.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton16ActionPerformed(evt);
            }
        });

        jButton17.setText("←");
        jButton17.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton17ActionPerformed(evt);
            }
        });

        jButton18.setText("C");
        jButton18.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton18ActionPerformed(evt);
            }
        });

        jButton19.setText("CE");
        jButton19.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton19ActionPerformed(evt);
            }
        });

        jButton20.setText("+/-");
        jButton20.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton20ActionPerformed(evt);
            }
        });

        jButton21.setText("√");
        jButton21.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton21ActionPerformed(evt);
            }
        });

        jButton22.setText("%");
        jButton22.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton22ActionPerformed(evt);
            }
        });

        jButton23.setText("1/x");
        jButton23.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton23ActionPerformed(evt);
            }
        });

        jButton24.setText("=");
        jButton24.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton24ActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                    .addComponent(txtPantalla)
                    .addGroup(layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                .addComponent(btn7, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                .addComponent(btn8, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                .addComponent(btn9, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                .addComponent(jButton8, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                .addComponent(jButton12, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                                    .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                        .addComponent(btn4, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(btn5, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(btn6, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                                    .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                        .addComponent(btn1, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(btn2, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(btn3, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                                    .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                                        .addComponent(jButton17, javax.swing.GroupLayout.PREFERRED_SIZE, 69, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(jButton19, javax.swing.GroupLayout.PREFERRED_SIZE, 71, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addGap(4, 4, 4)
                                        .addComponent(jButton18, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)))
                                .addGap(0, 0, Short.MAX_VALUE)))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(layout.createSequentialGroup()
                                .addComponent(jButton20, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                .addComponent(jButton21, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(jButton13, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(jButton14, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(jButton16, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(jButton15, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(jButton22, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(jButton23, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE)
                                    .addComponent(jButton24, javax.swing.GroupLayout.PREFERRED_SIZE, 75, javax.swing.GroupLayout.PREFERRED_SIZE))))))
                .addContainerGap())
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(txtPantalla, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jButton17)
                    .addComponent(jButton18)
                    .addComponent(jButton19)
                    .addComponent(jButton20)
                    .addComponent(jButton21))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btn7)
                    .addComponent(btn8)
                    .addComponent(btn9)
                    .addComponent(jButton13)
                    .addComponent(jButton22))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(btn4)
                    .addComponent(btn5)
                    .addComponent(btn6)
                    .addComponent(jButton14)
                    .addComponent(jButton23))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addGroup(layout.createSequentialGroup()
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(btn1)
                            .addComponent(btn2)
                            .addComponent(btn3)
                            .addComponent(jButton16))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(jButton8)
                            .addComponent(jButton12)
                            .addComponent(jButton15)))
                    .addComponent(jButton24, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                .addGap(22, 22, 22))
        );

        pack();
    }// </editor-fold>                        

    private void btn6ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "6";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void btn8ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "8";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void btn7ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "7";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void jButton15ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        p = txtPantalla.getText();
        txtPantalla.setText("");
        x = Double.parseDouble(p);
        p = "";
        c = 4;
    }                                         

    private void jButton24ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (c != 0) {
            if (c == 1) {
                x = x + Double.parseDouble(p);
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            } else if (c == 2) {
                x = x - Double.parseDouble(p);
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            } else if (c == 3) {
                x = x * Double.parseDouble(p);
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            } else if (c == 4) {
                if (Integer.parseInt(p) == 0) {
                    txtPantalla.setText("ERROR");
                } else {
                    x = x / Double.parseDouble(p);
                    txtPantalla.setText(String.valueOf(x));
                    p = String.valueOf(x);
                    c = 0;
                }
                cn = 1;
            } else if (c == 5) {
                x = 1 / Double.parseDouble(p);
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            } else if (c == 6) {
                x = (-1)*Double.parseDouble(p);
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            } else if (c == 7) {
                x = Math.sqrt(Double.parseDouble(p));
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            } else if (c == 8) {
                x = (x * Double.parseDouble(p))/100;
                txtPantalla.setText(String.valueOf(x));
                p = String.valueOf(x);
                c = 0;
                cn = 1;
            }
        }
    }                                         

    private void btn1ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "1";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void btn2ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "2";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void btn3ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "3";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void btn4ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        a = "4";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void txtPantallaActionPerformed(java.awt.event.ActionEvent evt) {                                            

    }                                           

    private void btn5ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "5";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void btn9ActionPerformed(java.awt.event.ActionEvent evt) {                                     
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "9";
        p = p + a;
        txtPantalla.setText(p);
    }                                    

    private void jButton13ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        p = txtPantalla.getText();
        txtPantalla.setText("");
        x = Double.parseDouble(p);
        p = "";
        c = 1;
    }                                         

    private void jButton14ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        p = txtPantalla.getText();
        txtPantalla.setText("");
        x = Double.parseDouble(p);
        p = "";
        c = 2;
    }                                         

    private void jButton16ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        p = txtPantalla.getText();
        txtPantalla.setText("");
        x = Double.parseDouble(p);
        p = "";
        c = 3;
    }                                         

    private void jButton8ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        if (cn != 0) {
            p = "";
            txtPantalla.setText("");
            cn = 0;
        }
        a = "0";
        p = p + a;
        txtPantalla.setText(p);
    }                                        

    private void jButton23ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        c = 5;
        jButton24ActionPerformed(evt);
    }                                         

    private void jButton20ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        c = 6;
        jButton24ActionPerformed(evt);
    }                                         

    private void jButton21ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        c = 7;
        jButton24ActionPerformed(evt);
    }                                         

    private void jButton22ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        p = txtPantalla.getText();
        txtPantalla.setText("");
        x = Double.parseDouble(p);
        p = "";
        c = 8;
    }                                         

    private void jButton19ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        p = "";
        txtPantalla.setText(p);
    }                                         

    private void jButton17ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        if (p.length() != 0){
            p = p.substring(0, p.length()-1);
            txtPantalla.setText(p);
        }
    }                                         

    private void jButton18ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        x = 0;
        p = "";
        txtPantalla.setText(p);
    }                                         

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(VentanaPrincipal.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new VentanaPrincipal().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton btn1;
    private javax.swing.JButton btn2;
    private javax.swing.JButton btn3;
    private javax.swing.JButton btn4;
    private javax.swing.JButton btn5;
    private javax.swing.JButton btn6;
    private javax.swing.JButton btn7;
    private javax.swing.JButton btn8;
    private javax.swing.JButton btn9;
    private javax.swing.JButton jButton12;
    private javax.swing.JButton jButton13;
    private javax.swing.JButton jButton14;
    private javax.swing.JButton jButton15;
    private javax.swing.JButton jButton16;
    private javax.swing.JButton jButton17;
    private javax.swing.JButton jButton18;
    private javax.swing.JButton jButton19;
    private javax.swing.JButton jButton20;
    private javax.swing.JButton jButton21;
    private javax.swing.JButton jButton22;
    private javax.swing.JButton jButton23;
    private javax.swing.JButton jButton24;
    private javax.swing.JButton jButton8;
    private javax.swing.JTextField txtPantalla;
    // End of variables declaration                   
}
![1 3](https://user-images.githubusercontent.com/49033575/57344842-6638f380-710e-11e9-85db-9308b51439bf.png)

Cuenca GitHub: EdisonAmendano
URLs: 
•	Calculador : https://github.com/EdisonAmendano/Interfaz-Grafica-de-Usuario---Calculadora.git

RESULTADO(S) OBTENIDO(S):

	Se aprendió a crear una interfaz gráfica de usuario en java. 
	La utilización correcta de las propiedades de la interfaz. 
CONCLUSIONES

	La interfaz de usuario en java es de gran utilidad ya que nos permite la interacción con el usuario de una manera más dinámica y menos confusa.


Nombre de estudiante: Edison Amendaño

Firma de estudiante: 

![Firma](https://user-images.githubusercontent.com/49033575/57344888-8cf72a00-710e-11e9-8c97-ec7c77d0c1a1.png)

