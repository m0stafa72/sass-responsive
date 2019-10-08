# sass-responsive
You can use the following methods for different devices
#mobile
// width < 480px
<br>
 <pre>
     body {
        @include mobile {
             font-family: 'font';
        }
     }
 </pre>
#lg-mobile
// width > 480px & < 768px
<br>
 <pre>
     body {
        @include lg-mobile {
             font-family: 'font';
        }
     }
 </pre>
#tablet
// width > 768px & < 1024px
 <pre>
     body {
        @include tablet {
             font-family: 'font';
        }
     }
 </pre>
#laptop
// width > 1024px & < 1200px
 <pre>
     body {
        @include laptop {
             font-family: 'font';
        }
     }
 </pre>
#lg-laptop
  // width > 1200px & < 1600px
   <pre>
       body {
          @include lg-laptop {
               font-family: 'font';
          }
       }
   </pre>
#desktop
// width > 1600px
  <pre>
     body {
        @include desktop {
             font-family: 'font';
        }
  </pre>
 }