!SLIDE subsection

# ACL

!SLIDE

# Profiles
## Admnistrator / Anonymous Users / Registered Users

!SLIDE

# Groupes

!SLIDE bullets

# Catégories:
* Verified
* Push Tag
* Push Branch
* Submit
* Code review
* Forge identity
* Owner
* Read access

!SLIDE

# Range
## de -2 à +2

!SLIDE

# Attribués sur une référence

!SLIDE code

# Exemple :

	Group       Reference Name 	Category     Range
	Registered  refs/heads/* 	Code Review  -1..+1
	Foo Leads   refs/heads/* 	Code Review  -2..+2
	QA Leads    -refs/heads/qa 	Code Review  -2..+2 

!SLIDE

# ACL configurable globalement ou par projet

!SLIDE subsection

# Revue de code

!SLIDE

# Verified
## -1 / 0 / +1

!SLIDE

# Code review
## -2 / -1 / 0 / +1 / +2

!SLIDE

# Si Verified AND Code review then **Submit**
