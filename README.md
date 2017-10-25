# CsharpTest
C sharp test project

Informations générales:
Idées générales :
choisir un logo a exporter ? (le glisser dans le dossier  ?)
Modification du format dans le logiciel (comme dans les exports)
	Calibration : 3 chiffres après la virgule, format 0.000
	Measure : 3 chiffres significatifs, format G3

https://www.simple-talk.com/sql/database-administration/pop-rivetts-sql-server-faq-no.5-pop-on-the-audit-trail/
Fonctionne pour la table mesuredata
Repasser sur les profiles pour modifier les droits (vrai nom / en ajouter) Bloquer chaque onglet recipe / bloquer note etc


Pour charger les combobox au lancement de la page dans le load : 
                if (cbo_reference.Items.Count > 0)
                {
                    cbo_reference.SelectedIndex = 0;
                    cbo_reference_SelectedIndexChanged(sender, e);
                }
            System.Windows.Forms.Help.ShowHelp(this, @"C:\Users\me\Documents\Visual Studio 2017\Projects\myProject\packages\Help.chm", HelpNavigator.Topic, "Recipe.html#Hpptol");
