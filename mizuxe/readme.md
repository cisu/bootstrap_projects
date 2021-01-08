if you want to over write bootstrap

1. @import bootstrap
   @import 'node_modules/bootstrap/scss/bootstrap';

2. Above change the rules 

*example*

* \$theme-colors: (
  'primary': #3292a6,
);*

* \$border-radius: 0 !default;*
* \$border-radius-lg: 0 !default;*
* \$border-radius-sm: 0 !default;*

@import 'node_modules/bootstrap/scss/bootstrap';