## Welcome to Garrett's Laboratory 




### Testing

While testing you should ensure that you are taking relative precautions to minimise mass destruction.

<script>
  window.intercomSettings = {
    app_id: "i37jck82"
  };
</script>
<script>(function(){var w=window;var ic=w.Intercom;if(typeof ic==="function"){ic('reattach_activator');ic('update',intercomSettings);}else{var d=document;var i=function(){i.c(arguments)};i.q=[];i.c=function(args){i.q.push(args)};w.Intercom=i;function l(){var s=d.createElement('script');s.type='text/javascript';s.async=true;s.src='https://widget.intercom.io/widget/i37jck82';var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);}if(w.attachEvent){w.attachEvent('onload',l);}else{w.addEventListener('load',l,false);}}})()</script>
<script>
   //#######################################################//
   // EXTRA JS CODE TO DISABLE GIF, EMOJI AND ATTACH ICONS  //
   //#######################################################//
   const intercom_css = document.createElement("style");       // Create CSS code to hide the icons
   intercom_css.type = "text/css";
   intercom_css.innerHTML = "#intercom-container .intercom-composer-upload-button {visibility: hidden;}";
   const interval = setInterval(() => {   // Intercept the Messenger iFrame as it loads
   var iframe = document.getElementsByName('intercom-messenger-frame')[0];
   var openLauncher = document.getElementsByClassName("intercom-launcher-open-icon")[0];

   if (iframe) {    // Check if the Intercom Messenger iframe code is present
      iframe.contentDocument.head.appendChild(intercom_css);   // Update the CSS for the iFrame
   }
   
   if (openLauncher) {
      openLauncher.addEventListener("click", function() {  // Also add an event listener to check for subsequent new conversation in the same session
         iframe.contentDocument.head.appendChild(intercom_css);  // In that event also update the CSS for the iFrame
      });
   clearInterval(interval);           // Allow the iFrame to continue loading
   }
}, 100);
</script>
