# cs3750-project-1-solved
**TO GET THIS SOLUTION VISIT:** [CS3750 Project 1 Solved](https://www.ankitcodinghub.com/product/cs3750-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;61286&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3750 Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<strong>Task I: </strong>Write THREE independent programs in three SEPARATE directories: a <strong><em>key generation</em></strong> program, a <strong><em>sender’s</em></strong> program, and a <strong><em>receiver’s</em></strong> program, to implement ONE of the following options of simplified cryptographic applications.

&nbsp;

<ul>
<li>In the<strong><em> key generation</em></strong> program (it is required for EACH of the following options) in the directory “<strong>KeyGen</strong>”,</li>
</ul>
<ol>
<li>Create a pair of RSA public and pr ivate keys for <strong>X</strong>, <strong><em>Kx<sup>+</sup></em></strong> and <strong><em>Kx<sup>–</sup></em></strong>;</li>
<li>Create a pair of RSA public and private keys for <strong>Y</strong>, <strong><em>Ky<sup>+</sup></em></strong> and <strong><em>Ky<sup>–</sup></em></strong>;</li>
<li>Get the modulus and exponent of each RSA public or private key and save them into files named “<em>key</em>”, “<em>XPrivate.key</em>”, “<em>YPublic.key</em>”, and “<em>YPrivate.key</em>”, respectively;</li>
<li>Take a 16-character user input from the keyboard and save this 16-character string to a file named “<em>key</em>”. This string’s 128-bit UTF-8 encoding will be used as the 128-bit AES symmetric key, <strong><em>Kxy</em></strong>, in your application.</li>
</ol>
&nbsp;

<strong>Option 1: Public-key encrypted message and its authentic digital digest </strong>• In this option, <strong>X</strong> is the <strong>sender</strong> and <strong>Y</strong> is the <strong>receiver</strong>.

<ul>
<li>In the <strong><em>sender’s</em></strong> program in the directory “<strong>Sender</strong>”, calculate <strong>RSA-En</strong> <em><sub>Ky+</sub></em> (<strong>AES-En </strong><em><sub>Kxy</sub></em> (S<strong>HA256 </strong>(M)) || M) 1 To test this program, the corresponding key files need to be copied here from the directory “KeyGen” 2 &nbsp;&nbsp; Read the information on the keys to be used in this program from the key files and generate <strong><em>Ky<sup>+</sup></em></strong> and <strong><em>Kxy</em></strong>.
<ul>
<li>Display a prompt “Input the name of the message file:” and take a user input from the keyboard. This user input provides the name of the file containing the message <strong>M</strong>.&nbsp; <strong>M</strong> can NOT be assumed to be a text message.&nbsp; The size of the message M could be much larger than 32KB.</li>
<li>Read the message, <em>M</em>, from the file specified in Step 3 piece by piece, where each piece is recommended to be a small multiple of 1024 bytes, calculate the SHA256 hash value (digital digest) of the entire message M, i.e., <strong>SHA256</strong>(M), SAVE it into a file named “<em>dd</em>”, and DISPLAY <strong>SHA256</strong>(M) in Hexadecimal bytes.</li>
<li>Calculate the <strong>AES</strong> <strong>Encryption</strong> of <strong>SHA256</strong>(M) using <strong><em>Kxy</em></strong> (NO padding is allowed or needed here. Question: how many bytes are there in total?), SAVE this AES cyphertext into a file named “<em>add-msg</em>”, and DISPLAY it in Hexadecimal bytes. APPEND the message M read from the file specified in Step 3 to the file “<em>message.add-msg</em>” piece by piece.</li>
<li>Calculate the <strong>RSA</strong> <strong>Encryption</strong> of (<strong>AES-En </strong><em><sub>Kxy</sub></em> (S<strong>HA256 </strong>(M)) || M) using <strong><em>Ky<sup>+</sup></em></strong> by reading the file “<em>add-msg</em>” piece by piece, where each piece is recommended to be 117 bytes if “RSA/ECB/PKCS1Padding” is used. (Hint: if the length of the last piece is less than 117 bytes, it needs to be placed in a byte array whose array size is the length of the last piece before being encrypted.) SAVE the resulting blocks of RSA ciphertext into a file named “<em>message.rsacipher</em>”.</li>
</ul>
</li>
<li>In the <strong><em>receiver’s</em></strong> program in the directory “<strong>Receiver</strong>”, using <strong>RSA</strong> and <strong>AES Decryptions </strong>to get S<strong>HA256 </strong>(M) and M, compare <strong>SHA256</strong>(M) with the locally calculated SHA256 hash of M, report hashing error if any, and then save M to a file.
<ul>
<li>To test this program, the corresponding key files need to be copied here from the directory “KeyGen”, and the file “<em>rsacipher</em>” needs to be copied here from the directory “Sender”.</li>
<li>Read the information on the keys to be used in this program from the key files and generate <strong><em>Ky<sup>– </sup></em></strong>and <strong><em>Kxy</em></strong>.</li>
<li>Display a prompt “Input the name of the message file:” and take a user input from the keyboard. The resulting message M will be saved to this file at the end of this program.</li>
<li>Read the ciphertext, C, from the file “<em>rsacipher</em>” block by block, where each block is recommended to be 128 byte long if “RSA/ECB/PKCS1Padding” is used. Calculate the <strong>RSA</strong> <strong>Decryption</strong> of <strong>C</strong> using <strong><em>Ky<sup>–</sup></em></strong> block by block to get <strong>AES-En </strong><em><sub>Kxy</sub></em> (S<strong>HA256 </strong>(M)) || M, and save the resulting pieces into a file named “<em>message.add-msg</em>”.</li>
<li>Read the first 32 bytes from the file “<em>add-msg</em>” to get the <strong><em>authentic digital digest</em></strong> <strong>AES-En </strong><em><sub>Kxy</sub></em> (S<strong>HA256 </strong>(M)), and copy the message <strong>M</strong>, i.e., the leftover bytes in the file “<em>message.add-msg</em>”, to a file whose name is specified in Step 3. (Why 32 bytes? Why is the leftover M?) Calculate the <strong>AES</strong> <strong>Decryption</strong> of this authentic digital digest using <strong><em>Kxy</em></strong> to get the <strong><em>digital digest</em></strong> <strong>SHA256</strong>(M), SAVE this digital digest into a file named “<em>message.dd</em>”, and DISPLAY it in Hexadecimal bytes.</li>
<li>Read the message <strong><em>M</em></strong> from the file whose name is specified in Step 3 piece by piece, where each piece is recommended to be a small multiple of 1024 bytes, calculate the SHA256 hash value (digital digest) of the entire message M, compare it with the digital digest obtained in Step 5, and display whether the digital digest passes the authentication check.</li>
</ul>
</li>
</ul>
&nbsp;

<strong>Option 2: symmetric-key encrypted message and its digital signature </strong>• &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this option, <strong>X</strong> is the <strong>sender</strong> and <strong>Y</strong> is the <strong>receiver</strong>.

<ul>
<li>In the <strong><em>sender’s</em></strong> program in the directory “<strong>Sender</strong>”, calculate <strong>AES-En</strong> <em><sub>Kxy</sub></em> (<strong>RSA-En </strong><em><sub>Kx</sub>–</em> (S<strong>HA256 </strong>(M)) || M) 1 To test this program, the corresponding key files need to be copied here from the directory “KeyGen” 2 &nbsp;&nbsp; Read the information on the keys to be used in this program from the key files and generate <strong><em>Kx <sup>–</sup></em></strong> and <strong><em>Kxy</em></strong>.
<ul>
<li>Display a prompt “Input the name of the message file:” and take a user input from the keyboard. This user input provides the name of the file containing the message <strong>M</strong>.&nbsp; <strong>M</strong> can NOT be assumed to be a text message.&nbsp; The size of the message M could be much larger than 32KB.</li>
<li>Read the message, <em>M</em>, from the file specified in Step 3 piece by piece, where each piece is recommended to be a small multiple of 1024 bytes, calculate the SHA256 hash value (digital digest) of the entire message M, i.e., <strong>SHA256</strong>(M), SAVE it into a file named “<em>dd</em>”, and DISPLAY <strong>SHA256</strong>(M) in Hexadecimal bytes.</li>
<li>Calculate the <strong>RSA</strong> <strong>Encryption</strong> of <strong>SHA256</strong>(M) using <strong><em>Kx <sup>–</sup></em></strong> (Question: how many bytes is the cyphertext?), SAVE this RSA cyphertext (the digital signature of <strong>M</strong>), into a file named “<em>ds-msg</em>”, and DISPLAY it in Hexadecimal bytes. APPEND the message M read from the file specified in Step 3 to the file “<em>message.ds-msg</em>” piece by piece.</li>
<li>Calculate the <strong>AES</strong> <strong>Encryption</strong> of (<strong>RSA-En </strong><em><sub>Kx</sub>–</em> (S<strong>HA256 </strong>(M)) || M) using <strong><em>Kxy</em></strong> by reading the file “<em>ds-msg</em>” piece by piece, where each piece is recommended to be a multiple of 16 bytes long. (Hint: if the length of the last piece is less than that multiple of 16 bytes, it needs to be placed in a byte array whose array size is the length of the last piece before being encrypted.)&nbsp; SAVE the resulting blocks of AES ciphertext into a file named “<em>message.aescipher</em>”.</li>
</ul>
</li>
<li>In the <strong><em>receiver’s</em></strong> program in the directory “<strong>Receiver</strong>”, using <strong>AES</strong> and <strong>RSA Decryptions </strong>to get S<strong>HA256 </strong>(M) and M, compare <strong>SHA256</strong>(M) with the locally calculated SHA256 hash of M, report hashing error if any, and then save M to a file.
<ul>
<li>To test this program, the corresponding key files need to be copied here from the directory “KeyGen”, and the file “<em>aescipher</em>” needs to be copied here from the directory “Sender”.</li>
<li>Read the information on the keys to be used in this program from the key files and generate <strong><em>K<sub>x</sub><sup>+</sup></em></strong> and <strong><em>Kxy</em></strong>.</li>
<li>Display a prompt “Input the name of the message file:” and take a user input from the keyboard. The resulting message M will be saved to this file at the end of this program.</li>
<li>Read the ciphertext, <strong>C</strong>, from the file “<em>aescipher</em>” block by block, where each block needs to be a multiple of 16 bytes long. (Hint: if the length of the last block is less than that multiple of 16 bytes, it needs to be placed in a byte array whose array size is the length of the last piece before being decrypted.)&nbsp; Calculate the <strong>AES</strong> <strong>Decryption</strong> of <strong>C</strong> using <strong><em>Kxy</em></strong> block by block to get <strong>RSA-En </strong><em><sub>Kx</sub></em>– (S<strong>HA256 </strong>(M)) || M, and save the resulting pieces into a file named “<em>message.ds-msg</em>”.</li>
<li>If using “RSA/ECB/PKCS1Padding”, read the first 128 bytes from the file “<em>ds-msg</em>” to get the <strong><em>digital signature</em></strong> <strong>RSA-En </strong><em><sub>Kx</sub></em>– (S<strong>HA256 </strong>(M)), and copy the message <strong>M</strong>, i.e., the leftover bytes in the file “<em>message.ds-msg</em>”, to a file whose name is specified in Step 3. (Why 128 bytes? Why is the leftover M?) Calculate the <strong>RSA</strong> <strong>Decryption</strong> of this digital signature using <strong><em>K<sub>x</sub></em><sup>+</sup></strong> to get the <strong><em>digital digest</em></strong> <strong>SHA256</strong>(M), SAVE this digital digest into a file named “<em>message.dd</em>”, and DISPLAY it in Hexadecimal bytes.</li>
<li>Read the message <strong><em>M</em></strong> from the file whose name is specified in Step 3 piece by piece, where each piece is recommended to be a small multiple of 1024 bytes, calculate and display the SHA256 hash value (digital digest) of the entire message M, compare it with the digital digest obtained in Step 5, display whether the digital digest passes the authentication check.</li>
</ul>
</li>
</ul>
&nbsp;

<strong>Option 3: Digital envelope including keyed hash MAC </strong>

<ul>
<li>In this option, <strong>X</strong> is the <strong>sender</strong>, <strong>Y</strong> is the <strong>receiver</strong>, <strong><em>Kxy</em></strong> is the random symmetric key generated by X.</li>
<li>In the <strong><em>sender’s</em></strong> program in the directory “<strong>Sender</strong>”, calculate S<strong>HA256 </strong>(<strong><em>Kxy</em></strong> || M || <strong><em>Kxy</em></strong>), <strong>AES-En </strong><em><sub>Kxy</sub></em> (M), and <strong>RSA-En</strong> <em><sub>Ky+</sub></em> (<strong><em>Kxy</em></strong>) 1 To test this program, the corresponding key files need to be copied here from the directory “KeyGen” 2 &nbsp;&nbsp;&nbsp;&nbsp; Read the information on the keys to be used in this program from the key files and generate <strong><em>Ky<sup>+</sup></em></strong> and <strong><em>Kxy</em></strong>.
<ul>
<li>Display a prompt “Input the name of the message file:” and take a user input from the keyboard. This user input provides the name of the file containing the message <strong>M</strong>.&nbsp; <strong>M</strong> can NOT be assumed to be a text message.&nbsp; The size of the message M could be much larger than 32KB.</li>
<li>WRITE <strong><em>Kxy</em></strong> to a file named “<em>kmk</em>”, read the message <strong>M</strong> from the file specified in Step 3 piece by piece, APPEND M to the file “<em>message.kmk</em>”, and finally APPEND<strong><em> Kxy</em></strong> to the file “<em>message.kmk</em>”.</li>
<li>Read <strong><em>Kxy</em></strong> || M || <strong><em>Kxy</em></strong> piece by piece from the file “<em>kmk</em>”, where each piece is recommended to be a small multiple of 1024 bytes, calculate the <strong><em>keyed hash MAC</em></strong>, i.e., the <strong>SHA256</strong> hash value of (<strong><em>Kxy</em></strong> || M || <strong><em>Kxy</em></strong>), SAVE this keyed hash MAC into a file named “<em>message.khmac</em>”, and DISPLAY it in Hexadecimal bytes.</li>
<li>Calculate the <strong>AES</strong> <strong>Encryption</strong> of <strong>M</strong> using <strong><em>Kxy</em></strong> by reading the file specified in Step 3 piece by piece, where each piece is recommended to be a multiple of 16 bytes long. (Hint: if the length of the last piece is less than that multiple of 16 bytes, it needs to be placed in a byte array whose array size is the length of the last piece before being encrypted.)&nbsp; SAVE the resulting blocks of AES ciphertext into a file named “<em>aescipher</em>”.</li>
<li>Calculate the <strong>RSA</strong> <strong>Encryption</strong> of <strong><em>Kxy</em></strong> using <strong><em>Ky<sup>+</sup></em></strong>. (Hint: if “RSA/ECB/PKCS1Padding” is used, what is the length of the resulting ciphertext?)&nbsp; SAVE the resulting RSA ciphertext into a file named “<em>rsacipher</em>”.</li>
</ul>
</li>
<li>In the <strong><em>receiver’s</em></strong> program in the directory “<strong>Receiver</strong>”, using <strong>RSA</strong> <strong>Decryption</strong> to get <strong><em>Kxy</em></strong>, <strong>AES Decryptions </strong>to get <strong>M</strong>, compare <strong>SHA256</strong>(<strong><em>Kxy</em></strong> || <strong>M</strong> || <strong><em>Kxy</em></strong>) with the locally calculated SHA256 hash of (<strong><em>Kxy</em></strong> || <strong>M</strong> || <strong><em>Kxy</em></strong>), and report hashing error if any.
<ul>
<li>To test this program, the corresponding key files need to be copied here from the directory “KeyGen”, and the files “<em>khmac</em>”, “<em>message.aescipher</em>”, and “<em>kxy.rsacipher</em>” need to be copied here from the directory “Sender”. (Hint:</li>
</ul>
</li>
</ul>
the file “<em>symmetric.key</em>” should NOT be copied here from the directory “KeyGen”.)

<ul>
<li>Read the information on the keys to be used in this program from the key file and generate <strong><em>Ky<sup>–</sup></em></strong>.</li>
<li>Display a prompt “Input the name of the message file:” and take a user input from the keyboard. The resulting message M will be saved to this file at the end of this program.</li>
<li>Read the ciphertext, <strong>C1</strong>, from the file “<em>rsacipher</em>”. Calculate the <strong>RSA</strong> <strong>Decryption</strong> of <strong>C1</strong> using <strong><em>Ky<sup>–</sup></em></strong> to get the random symmetric key <strong><em>Kxy</em></strong>, SAVE <strong><em>Kxy</em></strong> to a file named “<em>message.kmk</em>”, and DISPLAY <strong><em>Kxy</em></strong> in Hexadecimal bytes.</li>
<li>Read the ciphertext, <strong>C2</strong>, from the file “<em>aescipher</em>” block by block, where each block needs to be a multiple of 16 bytes long. (Hint: if the length of the last block is less than that multiple of 16 bytes, it needs to be placed in a byte array whose array size is the length of the last piece before being decrypted.)&nbsp; Calculate the <strong>AES</strong> <strong>Decryption</strong> of <strong>C2</strong> block by block using the <strong><em>Kxy</em></strong> obtained in Step 4 to get <strong>M</strong>, WRITE the resulting pieces of <strong>M</strong> into the file specified in Step 3, and also APPEND those resulting pieces of M to the file “<em>message.kmk</em>” created in Step 4.&nbsp; Finally APPEND <strong><em>Kxy</em></strong> after <strong>M</strong> to the file “<em>message.kmk</em>”.&nbsp; (Hint: at the end of this Step, <strong><em>Kxy</em></strong> || <strong>M</strong> || <strong><em>Kxy</em></strong> is written to the file “<em>message.kmk</em>”, and <strong>M</strong> is written to the file specified in Step 3.)</li>
<li>Read <strong><em>Kxy</em></strong> || M || <strong><em>Kxy</em></strong> piece by piece from the file “<em>kmk</em>”, where each piece is recommended to be a small multiple of 1024 bytes, calculate the <strong><em>keyed hash MAC</em></strong>, i.e., the <strong>SHA256</strong> hash value of (<strong><em>Kxy</em></strong> || M || <strong><em>Kxy</em></strong>), COMPARE this keyed hash MAC with the keyed hash MAC read from the file “<em>message.khmac</em>”, DISPLAY whether it passes the message authentication checking, and DISPLAY both keyed hash MACs in Hexadecimal bytes.</li>
</ul>
&nbsp;

<strong>Task II: Test your programs on the Virtual Servers in the cloud. </strong>

<ol>
<li>MAKE a directory “<strong>Project1</strong>” under your home directory on cs3750a.msdenver.edu and cs3750b.msudenver.edu, and three subdirectories “<strong>KeyGen</strong>”, “<strong>Sender</strong>”, and “<strong>Receiver</strong>” under “<strong>Project1</strong>”.</li>
<li>UPLOAD and COMPILE the <strong><em>key generation</em></strong> program under “Project1/KeyGen” on <strong>cs3750a</strong>.msudenver.edu, the <strong><em>sender’s</em></strong> program under “Project1/Sender” <strong>cs3750a</strong>.msudenver.edu, and the <strong><em>receiver’s</em></strong> program under “Project1/Receiver” on <strong>cs3750b</strong>.msudenver.edu.</li>
<li>You may the small text file CS3700.htm, the medium-sized non-text file HW1_CS3750, and the large file 01_Intro.pdf for testing. TEST your programs for all the possible cases including the cases where there isn’t a message authentication error and the cases where there is a message authentication error.</li>
</ol>
&nbsp;

<strong>Task III: Present your work and demo your programs on the Virtual Servers in class. </strong>

<ol>
<li>Using the message file provided by the instructor on the day of presentation to demo all of your three programs step by step.</li>
</ol>
Show the outputs and the files generated by your programs as your programs run.
