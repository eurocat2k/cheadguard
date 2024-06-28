# cheadguard
C/C++ header guard snippet for vsCode

## Install

1. click 'Manage' on left bottom.
2. Select 'User snippets' then
3a. Click on either 'New Global Snippets file...'
3b. or click on 'New snippet for <project>' whatever it is
4. Add a name to the snippet
5. Clear everything from the template, then paste the code snippet from this repo.
6. Save and close


## Usage
When user creates an empty C/C++ header file, simply get start typing the following text:

  ```guard```

pressing ENTER the empty file will be filled with the header guard contents.

## Example

**dummy.h** before snippet applied
```

```

after snippet applied
```
#ifndef __DUMMY_H__
#define __DUMMY_H__


#ifdef __cplusplus
extern "C" {
#endif


#ifdef __cplusplus
}
#endif

#endif // __DUMMY_H__
```
