# Daria Liamina

## Contacts:
* Location: Karaganda, Kazahstan
* E-mail: slon-zelenyj@gmail.com
* GitHub: [davlik-zlob](https://github.com/Davlik-Zlob)
* Discord: Daria Liamina#3430
* Telegram: [davlik_zlob](https://t.me/davlik_zlob)

## About me:
I'm 32 y.o. From Nizhnij Novgorod, but now I live in Karaganda. I want to eat, that's why I'm learning programming. And I'm in love with it, because it's interesting!
> Make love, not war!

## Code example:
``` 
function duplicateCount(text){
  let lowerText = text.toUpperCase();
  let dict = new Map();
  for (let substr of lowerText) {
    if (dict.has(substr)) {
      dict.set(substr, dict.get(substr) + 1);
    } else {
      dict.set(substr, 1);
    }
  }
  let res = 0;
  for (let [substr, count] of dict.entries()) {
    if (count > 1) {
      res++;
    }
  }
  return res;
}
```

## Education:
Minin Nizhny Novgorod State Pedagogical University,  
psychological and pedagogical faculty

## Work experience:
I have worked as
* a kindergarten teacher,
* remedial course teacher,
* educational psychologist,
* librarian,
* support specialist
* and specialist in the archaeological heritage department.  
But now I've chosen **a new way**.

## Languages:
* Russian - *native*
* English - *A2*