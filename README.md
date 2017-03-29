# Adding stringutil plugin to cordova Android platform
ionic plugin add stringutilsiru --save
# Javascript usage
cordova.exec(<br> function(success){alert(success)} <br>,
                  function(failed){alert(success)} <br>,
                  "StringUtilCordovaPlugin" <br>,
                  "coolMethod" <br>,
                  ["Joe Nishanth"] <br>);
