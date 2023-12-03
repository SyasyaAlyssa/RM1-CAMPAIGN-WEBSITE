<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="rm1.css">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <title>RM1 CAMPAIGN</title>
    </head>
    <body>
        <header>
            <img src="International_Islamic_University_Malaysia_logo.svg.png" alt="AN IIUM LOGO" 
            width="100" height="100" title="IIUM LOGO">
        
            <nav>
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#forms">Forms</a>
                <a href="#contact">Contact</a>
            </nav>

        </header>

            <section id="Home">
                <h1>Home</h1>
                <h2>RM1 CAMPAIGN</h2>
                <p style="text-align:center;"><img src="Let your contributions be perpetual for the pleasure of Allah swt (1).png" alt="A poster about donation" 
                width="1000" height="500" title="Donation Poster"></p>
                <p style="text-align:center;">Let your contributions be perpetual for the pleasure of Allah swt.</p>
                <p>The example of those who spend their wealth 
                    in the way of Allah is like a seed
                    [of grain] which grows seven spikes;
                    in each spike is a hundred grains.
                <br>
                    And Allah multiplies [His reward] for whom He wills.
                    And Allah is all-Encompassing and Knowing.”
                    (Al Baqarah:261)
                </p>
            </section>
        
            <section id="About">
                <h1>About</h1>
                <p>In 1999, the IIUM Endowment Fund (IEF) was founded. Its primary goal is to support our university's underprivileged 
                    and needy students who perform well academically but are unable to pay for their tuition and living expenses. 
                    The primary source of funding for the IIUM Ummatic Scholarship, student financial aid, and emergency fund is the IEF.
                <br>
                    IEF has started a number of initiatives to collect general donations from people, businesses, and organisations 
                    in order to fundraise for the needy students. Donors can take advantage of our endowment/ Waqf programme,
                    RM1 Campaign, Zakat payment, and Kafalah programme, among other products and services.
                    IEF has also participated in a few corporate partnerships to boost the funds' capabilities.  
                </p>
            </section>
        
            <section id="Forms">
                <h1>Forms</h1>
                <h3>PARTICIPATION IN RM1 CAMPAIGN—MONTHLY SALARY DEDUCTION FORM</h3>
                <br>
                <form>
                    <fieldset>
                    <legend>Form</legend>
            
                    <div>
                        <label for="name">Name:
                            <span aria-label="required">*</span>
                        </label>
                    <input id="name" type="text" name="name" title="Please enter full name only." required>
                    <onclick="printInput()"></Input>
                        </label>
                    </div>

                    <br>

                    <div>
                        <label for="Staff No.">Staff No.:
                            <span aria-label="required">*</span>
                        </label>
                    <input id="number" type="number" name="number" required/>
                        </label>
                    </div>

                    <br>

                    <div>
                        <label for="K/C/D/I/O">K/C/D/I/O:
                        </label>
                    <input id="text" type="text" name="text"/>
                        </label>
                    </div>
                    
                    <br>

                    <div>
                        <label for="Contact No.">Contact No.:
                            <span aria-label="required">*</span>
                        </label>
                    <input id="number" type="number" name="number" required/>
                        </label>
                    </div>

                    <br>

                    <div>
                        <label for="Email">Email:
                        </label>
                    <input id="email" type="email" name="email"/>
                        </label>
                    </div>

                    <br>

                    <div>
                        <label for="Amount to be deducted">Amount to be deducted:
                            <span aria-label="required">*RM</span>
                        </label>
                        <input type="number" min="1.00" max="1.00" step="0.01" 
                    title="Value must be a minimum/maximum of RM1.00" required>
                    <onclick="printInput()"></Input>
                    </label>
                    </div>
            
                    <br>

                    <div>
                        <label for="The above salary deduction will take effect from">The above salary deduction will take effect from:
                            <span aria-label="required"></span><br>
                        </label>
                        <input type="date" min="2023-01-01" max="2023-12-31"
                    title="Value must be in YYYY-MM-DD" required>
                        <label for="The above salary deduction will take effect from">until:
                            <input type="date" min="2023-01-01" max="2023-12-31"
                            title="Value must be in YYYY-MM-DD" required>
                        <span aria-label="required"></span> or further notice.
                        </label>
                    <onclick="printInput()"></Input>
                    </label>
                    </div>

                    <br>
                    
                    <div>
                        <label for="For Kuliyyah of">For Kuliyyah of
                        </label>
                    <input id="text" type="text" name="text"/>
                        </label>
                    </div>

                    <br>
                    
                    <div class="button-container">
                        <button id="Submit">Submit</button>
                    </div>
        
                    </fieldset>
            
                </form>
            </section>
        
            <section id="Contact">
                <h1>Contact</h1>
                <p>IIUM ENDOWMENT FUND
                <br>Level 3,
                <br>Rectory International Islamic University Malaysia,
                <br>P.O Box 10,
                <br>50728 Kuala Lumpur,
                <br>Tel: 03 6196 4268
                <br>Email: ief@iium.edu.my 
                <br>Website:www.ief.iium.edu.my/ief
                <br>Facebook:www.facebook.com/ief.official/
                </p>
            </section>

            <footer>
                <p>2023 IIUM RM1 Campaign. All rights reserved.</p>
            </footer>
        
    </body>
    </html>

