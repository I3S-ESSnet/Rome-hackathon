# VTL examples

## Controls

string(junsenue-CI-0-IP-3)!='' and
(junsenue-CI-0-IP-3 &lt; xs:date(concat(junsenue-CI-0-IP-1,'-06-01'))
or junsenue-CI-0-IP-3 &gt; xs:date(concat(junsenue-CI-0-IP-2,'-05-31')))

## Conditioned labels

How many rooms have you in your
{
if ($LGT$='1') then 'house'
else if ($LGT$='2') then 'apartment'
else if ($LGT$='3') then 'barge'
else 'lodgement'
}?
