<template>
  <div class="hello" id="page-top">

    <!-- Navigation-->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top " id="mainNav">
        <div class="container" >
            <a class="navbar-brand" href="#page-top">
                <!-- <img src="assets/img/navbar-logo.svg" alt="..." /> -->
                <h4>HARIRI ALI</h4>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                Menu
                <i class="fas fa-bars ms-1"></i>
            </button>
            <div class="collapse navbar-collapse" id="navbarResponsive">
                <ul class="navbar-nav text-uppercase ms-auto py-4 py-lg-0">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#Projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Masthead-->
    <header class="masthead">
        <div class="container">
            <div class="masthead-subheading">Welcome To My Portfolio!</div>
            <div class="masthead-heading text-uppercase">It's Nice To Meet You</div>
            <a class="btn btn-primary btn-xl text-uppercase" href="#skills">Tell Me More</a>
        </div>
    </header>

        <!-- ======= About Section ======= -->
        <section id="about" class="about-mf sect-pt4 route">
            <div class="container">
              <div class="row">
                <div class="col-sm-12">
                  <el-card class="box-card">
                    <div class="row">
                      
                        <div class="row">
                          <div class="col-sm-6 col-md-6">
                            <div class="about-img">
                              <img src="../assets/img/profile.jpg" class="img-fluid rounded b-shadow-a" style="width:100%;height:100%; border-radius: 30px;" alt="">
                            </div>
                          </div>
                          <div class="col-sm-6 col-md-6">
                            <div class="about-info">
                              <h4 class="title-left">Personal Info</h4> <br/>
                              <div style="margin: 20px 30px;">
                              <p><span class="title-s">Name: </span> <span> HARIRI ALI</span></p>
                              <p><span class="title-s">Profile: </span> <span> web and mobile app developer</span></p>
                              <p><span class="title-s">Email: </span> <span> hariri.ali.official@gmail.com</span></p>
                              <p><span class="title-s">Phone: </span> <span> (+213) 669-21-21-22</span></p></div>
                            </div>
                            <div class="socials" style="">
                      <ul>
  <li>
    <a href="https://www.facebook.com/ali.sba.902">
      <i class="fab fa-facebook-f icon"></i>    </a>
  </li>
  <li>
    <a href="https://www.instagram.com/ali.sba.22/"><i class="fab fa-instagram icon"></i></a>
  </li>
  <li>
    <a href="https://dz.linkedin.com/in/ali-hariri-b88721185"><i class="fab fa-linkedin-in icon"></i></a></li>
  <li>
    <a href="#"><i class="fab fa-github icon"></i></a></li>
</ul>
                      </div>
                          </div>
                        </div>
                        <!-- <div class="skill-mf">
                          <p class="title-s">Skill</p>
                          <span>vuejs</span> <span class="pull-right">70%</span>
                          <div class="progress">
                            <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100"></div>
                          </div>
                          <span>nodejs</span> <span class="pull-right">60%</span>
                          <div class="progress">
                            <div class="progress-bar" role="progressbar" style="width: 60%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                          </div>
                          <span>java</span> <span class="pull-right">65%</span>
                          <div class="progress">
                            <div class="progress-bar" role="progressbar" style="width: 65%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                          </div>
                          <span>C++</span> <span class="pull-right">75%</span>
                          <div class="progress">
                            <div class="progress-bar" role="progressbar" style="width: 75%" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
                          </div>
                        </div> -->
                      </div>
                      <div class="row">
                      <div class="col-md-12">
                        <div class="about-me pt-4 pt-md-0">
                          <div class="title-box-2">
                            <h5 class="title-left">
                              About me
                            </h5>
                          </div>
                          <p class="lead">
                            HARIRI ALI is a freelance developer with more then one year in the field to helping a broad range of clients (individuals,companies and startups) to start,develop or grow their businesses
                          </p>
                          <p class="lead">
                           ALI is 4 grade student in ESI "ecole superieure d'informatique" specializes in developing web and mobile applications, including the product coding, hosting and search engine optimisation.
                          </p>
                          <!-- <p class="lead">
                            Nulla porttitor accumsan tincidunt. Quisque velit nisi, pretium ut lacinia in, elementum id enim.
                            Nulla porttitor accumsan
                            tincidunt. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.
                          </p> -->
                        </div>
                      </div>
                      </div>
                    
                  </el-card>
                </div>
              </div>
            </div>
          </section><!-- End About Section -->


          <!-- Portfolio Grid-->
          <section class="page-section bg-light" id="Projects">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">MY PROJECTS</h2>
                    <h3 class="section-subheading text-muted">Some of the projects I worked on</h3>
                </div>
                <div class="row">
                    <!-- items -->
                   

                   <el-card style="margin: 20px 0px;padding:15px" class="box-card">
                     <div class="container">
                    <div class="row row-cols-1">
                      <div class="col-md-6">
                         <img src="../assets/project01.jpg" alt="esi wether station logo" style="width:100%;height:100%; border-radius: 30px; -moz-box-shadow: 10px 10px 50px #ccc;
                            -webkit-box-shadow: 10px 10px 50px #ccc;
                            box-shadow: 10px 10px 50px #ccc;" >
                          
                      </div>

                      <div class="col-md-6">
                        
                          
                          <h4 class="title-left">Esi Wether Station</h4>
                          <br/>
                         
                         <p>Esi Weather is a multidisciplinary project made in
ESI-SBA, it represent an Intelligent, connected
system for the acquisition, analysis and processing of
remote meteorological data, with a complete display
via two interfaces (web and mobile). The system is
also expandable (both hardware and software) to
meet the needs of any user and allow the autonomy
of the entire system. The project was presented to
ESI-SBA and COC'2021.
                         </p>
                         <br/>
                         <h6>Technologies</h6>
                        <el-row>
                          <el-col :span="6">html</el-col>
                          <el-col :span="4">css </el-col>
                          <el-col :span="7">java script</el-col>
                          <el-col :span="7">java (android studio)</el-col>
                        </el-row>
                        <br/>
                        <h6>some things</h6>
                        <el-row>
                          <el-col :span="8">vuejs</el-col>
                          <el-col :span="8">nodejs (express)</el-col>
                          <el-col :span="8">java</el-col>
                        </el-row>
                        <br/>
                        <el-button type="primary" >detailes</el-button>
                    <el-button type="primary" disabled>live demo</el-button>
                    </div>
                    
                  </div></div>
                   </el-card>
                   <el-card style="margin: 20px 0px;padding:15px" class="box-card">
                     <div class="container">
                    <div class="row row-cols-1">
                      <div class="col-md-6"> <img src="../assets/project02.png" alt="esi wether station logo" style="width:100%;height:100%; border-radius: 30px;-moz-box-shadow: 10px 10px 50px #ccc;
      -webkit-box-shadow: 10px 10px 50px #ccc;
      box-shadow: 10px 10px 50px #ccc;" > 
                      </div>
                      <div class="col-md-6">
                      
                         <h4 class="title-left">Healthline </h4>
                         <br/>
                         
                         <p>The Design and realization of a Web/Mobile application for medical file management by the Preventive Medicine Unit (PMU) of ESI SBA.
                         </p>
                         <br/>
                         <h6>Technologies</h6>
                        <el-row>
                          <el-col :span="8">html</el-col>
                          <el-col :span="8">css </el-col>
                          <el-col :span="8">java (android studio)</el-col>
                          <el-col :span="8">sqlite</el-col>
                          <el-col :span="8"></el-col>
                          <el-col :span="8"></el-col>
                        </el-row>
                        <br/>
                        <h6>Freamworks</h6>
                        <el-row>
                          <el-col :span="8">vuejs</el-col>
                          <el-col :span="8">nodejs (express)</el-col>
                          <el-col :span="8"></el-col>
                        </el-row>
                        <br/>
                        <el-button type="primary">detailes</el-button>
                        <el-button type="primary">live demo</el-button>
                      </div>
                      
                    </div>
                     </div>
                     
                   </el-card>
                  

                   

                   
                   
                    <!-- <el-row>
                      <el-col :span="8">
                        <el-card class="box-card" style="margin: 5px;">
                          hello
                        </el-card>
                      </el-col>
                      <el-col :span="8">
                        <el-card class="box-card" style="margin: 5px;">
                          coco
                        </el-card>
                      </el-col>
                      <el-col :span="8">
                        <el-card class="box-card" style="margin: 5px;">
                          slt
                        </el-card>
                      </el-col>
                    </el-row>
                        <el-row>
                      <el-col :span="8">
                        <el-card class="box-card" style="margin: 5px;">
                          hello
                        </el-card>
                      </el-col>
                      <el-col :span="8">
                        <el-card class="box-card" style="margin: 5px;">
                          coco
                        </el-card>
                      </el-col>
                      <el-col :span="8">
                        <el-card class="box-card" style="margin: 5px;">
                          slt
                        </el-card>
                      </el-col>
                    </el-row> -->
                    
                </div>
            </div>
          </section>

          

          <!-- ======= Contact Section ======= -->
    <section id="contact" class="paralax-mf footer-paralax bg-image sect-mt4 route" style="background-image: url(../assets/img/overlay-bg.jpg)">
        <div class="overlay-mf"></div>
        <div class="container">
          <div class="row">
            <div class="col-sm-12">
              <div class="contact-mf">
                <div id="contact" >
                  <el-card class="box-card-contact">
                  <div class="row">
                    <div class="col-md-6">
                      <div class="title-box-2">
                        <h5 class="title-left">
                          Send Message Us
                        </h5>
                      </div>
                        <el-input v-model="formData.name" placeholder="Your name" style="margin: 10px 0px;"></el-input> 
                        <el-input v-model="formData.email" placeholder="Your Email" style="margin: 10px 0px;"></el-input> 
                        <el-input v-model="formData.subject" placeholder="Subject" style="margin: 10px 0px;"></el-input> 
                        <el-input v-model="formData.message" :rows="5" type="textarea" placeholder="Message" style="margin: 10px 0px;"></el-input> 
                        <el-button type="primary" round style="margin:10px 0px" @click="sendEmail"> Send the message </el-button>
                    </div>
                    <div class="col-md-6">
                      <div class="title-box-2 pt-4 pt-md-0">
                        <h5 class="title-left">
                          Get in Touch
                        </h5>
                      </div>
                      <div class="more-info">
                        <p class="lead">
                          Have you:
                          <ul class="list-ico">
                          <li><span class=""></span>  an idea and you looks for a developer?</li>
                          <li><span class=""></span>  a business and want to take advantage from the internet ?</li>
                          <li><span class=""></span>  any questions or feedbacks ?</li>
                          
                        </ul>
                          please feel free to contact me. 
                        </p>
                        
                          <img src="../assets/phone.svg" style="hight:24px;width:24px;"/>  (+213) 669-21-21-22 <br/><br/>
                          <img src="../assets/email.svg" style="hight:24px;width:24px;"/> hariri.ali.official@gmail.com<br/>
                        
                      </div>
                      <br/>
                      <div class="socials" style="">
                      <ul>
  <li>
    <a href="https://www.facebook.com/ali.sba.902">
      <i class="fab fa-facebook-f icon"></i>    </a>
  </li>
  <li>
    <a href="https://www.instagram.com/ali.sba.22/"><i class="fab fa-instagram icon"></i></a>
  </li>
  <li>
    <a href="https://dz.linkedin.com/in/ali-hariri-b88721185"><i class="fab fa-linkedin-in icon"></i></a></li>
  <li>
    <a href="#"><i class="fab fa-github icon"></i></a></li>
</ul>
                      </div>
                      
                    </div>
                  </div>
                  </el-card>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section><!-- End Contact Section -->
  

    
<!-- ======= Footer ======= -->
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="copyright-box">
            <p class="copyright">&copy; Copyright <strong>HARIRI ALI</strong>. All Rights Reserved 2021</p>
            <div class="credits">
              Designed by <a href="#">HARIRI ALI</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer><!-- End  Footer -->

  <div id="preloader"></div>
  <a href="#" class="back-to-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>



  
  </div>
</template>

<script>
import emailjs from 'emailjs-com';
export default {
  data() {
    return {
      formData:{
        name: "",
        email: "",
        subject: "",
        message: ""
      },
      name: "",
      props: {
        msg: String,
      },
    };
  },
  methods: {
    sendEmail() {
      try {
        emailjs.send('service_dgukqy9', 'template_ziiud8f',this.formData,
        'user_kiL2G409pIe4Z9n09Wkdw' );
        this.$message({
        title: 'Success',
        message: 'message send :)',
        type: 'success',
      });

      } catch(error) {
          console.log({error})
      }
      // Reset form field
      this.name = ''
      this.email = ''
      this.message = ''
    },
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box-card {
  border-radius: 30px;
}
.box-card-contact {
  border-radius: 10px;
}
</style>
