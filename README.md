# Grass

A sass quality assurance tool

## Don'ts:

### Not using variables

hexcodes appearing more than once. or just make every color a variable.

font sizes not being reused

media queries / breakpoints not being reused.
  

### Nesting more than three

    div {
      p {
        a{
          span{
            /* this is bad! */
          }
        }
      }
    }

### Hardcoding Vendor Prefixes

You should use a mixin of post-processor.

### Selectors appearing in more than one file:

    afile.scss:
    
    .selector{
      //stuff
    }
    
    
    
    anotherfile.scss:
    
    .selector{
      //some more stuff
    }



