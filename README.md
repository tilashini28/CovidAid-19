# CovidAid-19

        <section class="signup">
            <!-- <img src="images/signup-bg.jpg" alt=""> -->
            <div class="container">
                <div class="signup-content">
                    <form method="post" id="testerregister" class="signup-form" action="register.php" >
					
                        <h2 class="form-title">Create account</h2>
                        <div class="form-group">
                            <input type="text" class="form-control" name="username" id="name" placeholder="Username"/>
                        </div>
						<div class="form-group">
                            <input type="password" class="form-input" name="password" id="password" placeholder="Password"/>
                            <span toggle="#password" class="zmdi zmdi-eye field-icon toggle-password"></span>
                        </div>
                        <div class="form-group">
                            <input type="text" class="form-input" name="name" id="name" placeholder="Name"/>
                        </div>
						<div class="form-group">
                            <input type="text" class="form-input" name="address" id="address" placeholder="Address"/>
                        </div>
						<div class="form-group">
                            <input type="text" class="form-input" name="centreName" id="centreName" placeholder="CentreName"/>
                        </div>
						
						<p>UserType</p>
						 <input type="radio" id="officer" name="userType" value="officer">
						<label for="officer">Officer</label>
						<br>
						 <input type="radio" id="patient" name="userType" value="patient">
						<label for="patient">Patient</label>
						<br>
						<br>
						
                        <div class="form-group">
                            <input type="submit" name="submit" id="submit" class="form-submit" value="Sign up"/>
                        </div>
                    </form>
                    <p class="loginhere">
                        Have already an account ? <a href="TesterLogin.php" class="loginhere-link">Login here</a>
                    </p>
                </div>
            </div>
        </section>
