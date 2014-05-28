Požadavky na systém a jeho omezení
----------------------------------------------------------------------------------------------------

Požadavky na funkci systému
...................................................

Požadavky které jsou kladeny na funkci systému.

Hlavním cílem projektu je usnadnit vytváření validačních sad a
jejich použití pro validaci velkého objemu obrazových dat.

1. Z pohledu zájemce o validaci obrazových dat
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. systém poskytuje různé druhy validací pro různé formy balíků dat
#. systém umí validovat xml podle schematu
#. systém umí kontrolovat, za balík dat obsahuje všechny soubory
#. systém umí kontrolovat, zda jsou hodnoty dat ve správných mezích 
#. systém uchovává status žádostí o validaci
#. systém poskytuje přístup k žádostem o validaci
#. systém poskytuje přehled žádostí o validaci
#. systém umožňuje zpracování velikého objemu datových
#. systém poskytuje REST api pro validaci balíčků a pro přehled o validaci
#. systém spojuje validaci obrazovou s validací metadat
#. systém poskytuje ftp přístup pro upload dat k validaci


2. Z pohledu pracovníka knihovny
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. systém poskytuje možnost vytvořit sadu pravidel pro validaci – za pomoci web rozhraní
#. systém umí sadu pravidel pro validaci exportovat - ve formátu xml
#. systém umí sadu pravidel pro validaci importovat - ve formátu xml

3. Z pohledu systému
~~~~~~~~~~~~~~~~~~~~~~

#. systém využívá knihovny projektu Differ k validaci obrazových dat

Omezení systému
............................

