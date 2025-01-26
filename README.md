# BASH-Colors
## Usage
At any point you wish to use these colors, `source colors.sh` to get all variables, and then use 
```bash
echo -e "This word is: ${RED}Red$DEFAULT while all these others are not
```

![image](https://github.com/user-attachments/assets/df9fe1bb-e99b-4b43-9e34-2e7f652cf9a1)

Also works for the PS1 Environment Variable
```bash
PS1="$BOLD${RED}test${DEFAULT}:${BLUE}\w${NORMAL}\$ "
```

## Available Colors:
![image](https://github.com/user-attachments/assets/63f5912b-bda1-4995-844e-782d7e444146)


Styles can all be combined at the same time, while colors/background colors will overwrite each other
