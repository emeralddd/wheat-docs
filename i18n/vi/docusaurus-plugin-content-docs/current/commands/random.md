---
sidebar_position: 4
---

# Ngẫu nhiên

In this documentation, we will use default prefix is `e`.

## COINFLIP

> Flip a coin
>
> #### Syntax
>
> `ecoinflip`
>
> #### Aliases
>
> `cf` `coin` `flip` `xu` `lat` `latdongxu` `latxu`
>
> #### Example
>
> `ecoinflip`

## DICE

> Roll some dices
>
> #### Syntax
>
> `edice [number of faces in first dice] [number of faces in second dice] ... [number of faces in nth dice]`
>
> If you don't provide any faces of any dices, default will be a dice has 6 faces
>
> #### Aliases
>
> `xucxac` `xingau` `doxingau` `tungxucxac` `xn` `xx`
>
> #### Example
>
> `edice`
>
> `edice 6`
>
> `edice 10 12 20`

## LOREMIPSUM

> Generate a random Dummy Text
>
> #### Syntax
>
> `eloremipsum <DD/MM>`
>
> #### Aliases
>
> `li` `lorem` `ipsum` `dummy`
>
> #### Example
>
> `eloremipsum`

## PASSWORD

> Generate a random strong password
>
> #### Syntax
>
> `epassword <length>`
>
> The length must be a number, greater than 8 and less than 100.
>
> #### Aliases
>
> `pass` `mk` `passgen` `autopass` `taomk` `matkhau`
>
> #### Example
>
> `epassword 12`

## PICK

> Choose an option from a list
>
> #### Syntax
>
> `epick <first option>,<second option>,[third option],[forth option],...`
>
> #### Aliases
>
> `choose` `chon`
>
> #### Example
>
> `epick wheat,bot,hello`

## RAND

> Choose a random number in range
>
> #### Syntax
>
> `erand [min boundary (max)] [max boundary]`
>
> If you don't provided any arguments, default range will be [1, 100].
>
> If you only provided one argument, range will be [1, argument you provided].
>
> #### Aliases
>
> `rd` `ngaunhien` `batky` `rdm` `r`
>
> #### Example
>
> `erand`
>
> `erand 10`
>
> `erand 10 100`

## RDATE

> Give a random date in range
>
> #### Syntax
>
> `erdate [DD/MM/YYYY] [DD/MM/YYYY]`
>
> If you don't provided any arguments, default will be after 01/01/1970.
>
> If you only provided one argument, range will be after 01/01/1970 and before the date you provided.
>
> #### Aliases
>
> `randomdate` `ngaunhienngay` `datebetween`
>
> #### Example
>
> `erdate`
>
> `erdate 09/12/2020`
>
> `erdate 09/12/2000 09/12/2020`

## REMOJI

> Give a random emoji from a random server which bot is joined!
>
> #### Syntax
>
> `eremoji`
>
> #### Aliases
>
> `re` `emoji` `randomemoji`
>
> #### Example
>
> `eremoji`

## RTIME

> Give a random time in range
>
> #### Syntax
>
> `rtime [hh:mm] [hh:mm]`
>
> If you don't provided any arguments, default will be after 00:00 and before 23:59.
>
> If you only provided one argument, range will be after 00:00 and before the time you provided.
>
> #### Aliases
>
> `randomtime` `ngaunhiengio` `timebetween`
>
> #### Example
>
> `ertime`
>
> `ertime 11:11`
>
> `ertime 09:12 12:09`
