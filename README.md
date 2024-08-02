# **Installing JDK version 17 on Ubuntu VM **
 
 ## **Using APT (Advanced Packet Tool) Packet Manager. **
 <a href="https://bluevps.com/blog/how-to-install-java-on-ubuntu">Reference website to install jdk -17</a>

1. Before Installing Java on our System, Check either Java is present or not.
2. The Following command helps to check version is installed or need to install.
   **java --version**

3. The below result shows that Java is not installed on this system. If you receive this terminal output, you need to install Java.
<a href="https://lh3.googleusercontent.com/Dh5sRcg1xDmbkhHcp5nsUO21Ajm7W3qdHIf3W9HPpmnDDOR9XWknrK7PTJ9ZjBUfniEy5a3YeN38Wm5YuHrBRzVJTR2zuO9zkMy2s0e8jsLDXsQ8xGYUYCKM3XT63dgOjs-Cf3yKzlYpJQ8i8nVuhg">Result iamge</a>

To install the OpenJDK Java version, first update your system apt repositories using the command below:
   **sudo apt update**
<a href="https://lh5.googleusercontent.com/5qUar7gLKTf9VaqEcSW75QttjXF7IVFpuACiGYtR3UyO-4wS95mMSH3NbugquJyG9hdnzm13OwZnZ1Vp3ysBUPXpKspxFe5aqtuq1N4tQaTyrNJ_HuolRUGYv6NXhY9odRawitRPOQgCfD0P8Znhhw">Terminal Image aafter using command</a>

## Search OpenJDK using Apt Cache
The Ubuntu 22.04 repository, by default, includes the OpenJDK. It is an open-source version of JDK and JRE. Therefore, you can search the OpenJDK in the apt repository using the following command:
**sudo apt-cache search openjdk**
<a href="https://lh4.googleusercontent.com/Xn-rG0_r-2gvzzvAKecYQDKScfuzc_3du0lHSmuGHqZpLP0QK2fo-0cuOvdx58_6gPA2R_sv1iZ65BrWziQfcksst3ecqJ21FEbswLD6GCwt9Xf14_Af7v_tfTpPy4hUvaG0r2xxfhk2JtDYSytAIg">Terminal after searching jdk using apt cache</a>

## Install OpenJDK-17 Java on Ubuntu
Choose the suitable version of OpenJDK and install it using the apt repository. 
**sudo apt install openjdk-17-jdk**
<a herf="https://lh3.googleusercontent.com/vvKUvwMkvDZfeBBJb40L56I1IfbnvrJk6zcVdvRRBq2A9-XanRQR3zPTjNCG65WaQ7XpE_c4y1N29Zom3Z7oJTUL7d9Xa7cQ_D-RZ3sj9TdthB-vKMeySvpuafFwLhsxu8-dEyiZZ52veP6sEfTjzw">Click here</a>

## Verify Java Installation
Now, verify if Java is correctly installed on Ubuntu or not. Check the currently installed Java version with the following command:
<a herf="https://lh3.googleusercontent.com/UDBFf6DSS2Mt7sxVFviOlOEmb9-WpL2lKU3in9_dYvvHeckz8ybwDyTedBo9UUq7766_rHrv63pM9tn6hAZtK5kXREeGBD_An1EgANRbCo1Ct1latDXldLZfKimUrynMA0Q0B3m5WhGjUl76QUardQ">click here</a>
