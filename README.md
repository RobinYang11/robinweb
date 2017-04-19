# Ebook needs
## user module
### user attributes
- 1.id_int_notnull  : primary key,auto-increment.
- 2.name_varchar(30):true name on identity card.
- 3.idNumber_varchar(20):id number on identity card.
- 4.nickName_varchar(40):whatever character.
- 5.occupationId_varchar(40):occupatiion.
- 6.schoolId_int:which school.
- 7.companyId_int:company.
- 8.area_varchar(40):place.
- 9.telephoneNumber_varchar(20):phoneNumber.
- 10.email_varchar(40):email
### demands
- 1.people can register by email.
- 2.people can register by telephoneNumber.
- 3.people can register by wchat.
##　note module
### note attributes
- id_int:primary key ,auto-increment.
- asid-int:basic unit of a note.
- chapter_varchar(100): the name of the chapter.
- content_text:the main content of the note,written by markdown.
- creatorID_int:autocomplete with  current user.
- creatorTime_varchar(40):autocomplete with current date.
### demands
- 1.用户可以通过前端创建note，在后台则创建一个note表。创建完表之后，用户可以增加章，如果有节，则在章的基础上增加小节.


