using System;

namespace Test
{
	class Program
	{
		public static void Main(string[] args)
		{
			
			int spieler_sieg = 0; //Definiert die Siege als Null
			int comp_sieg = 0;
			int unentschieden = 0; //Nicht benutzt
						
			string Zeile1 = "#########################################################";
			string Zeile2 = "##    Willkommen bei Schere, Stein, Papier-Supreme!    ##";			
			
			Console.WriteLine("{0, 10}", Zeile1); // Wieso kein Abstand von 10 Zeichen?
			Console.WriteLine("{0}", Zeile2);
			Console.WriteLine("{0}\n", Zeile1);
			
		noname:
			Console.WriteLine("Wie heisst du?");
			string Spielername = Console.ReadLine();
			
			if(Spielername == "")
			{
				Console.WriteLine("Du hast keinen Namen?\nVersuch es noch einmal.\n");
				goto noname;
			}

			else;
				Console.WriteLine("\nDanke für's mitspielen, {0}.\n", Spielername);
			
			Console.WriteLine("Die Regeln sind wie folgt:\nPapier schlägt Stein\nStein schlägt Schere\nSchere schlägt Papier\n");
			
			// Hier beginnt das Spiel
		spielbeginn:
			Console.WriteLine("Was wählst du?");
			string input = Console.ReadLine();
			string[] variablen = {"Schere", "Stein", "Papier"}; //Erstellt array für Möglichkeiten
			Random spiel = new Random();
			int index = spiel.Next(variablen.Length); //Erstellt Zufall innerhalb des array "variablen"
			Console.WriteLine("\nComputer wählt {0}.", variablen[index]);
			Console.WriteLine("Du wählst {0}.", input);
			
			if(input == "Schere")
			{
				if((input == "Schere") & (variablen[index] == "Schere"))
			{
				Console.WriteLine("Unentschieden! Beide erhalten einen Punkt.\n");
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, ++spieler_sieg, ++comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
				else if((input == "Schere") & (variablen[index] == "Stein"))
			{
				Console.WriteLine("Du verlierst! Computer erhält einen Punkt.\n");
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, spieler_sieg, ++comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
				else if((input == "Schere") & (variablen[index] == "Papier"))
			{
				Console.WriteLine("Du gewinnst! {0} erhält einen Punkt.\n", Spielername);
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, ++spieler_sieg, comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
			}
			
			else if(input == "Stein")
			{
				if((input == "Stein") & (variablen[index] == "Stein"))
			{
				Console.WriteLine("Unentschieden! Beide erhalten einen Punkt.\n");
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, ++spieler_sieg, ++comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
				else if((input == "Stein") & (variablen[index] == "Papier"))
			{
				Console.WriteLine("Du verlierst! Computer erhält einen Punkt.\n");
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, spieler_sieg, ++comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
				else if((input == "Stein") & (variablen[index] == "Schere"))
			{
				Console.WriteLine("Du gewinnst! {0} erhält einen Punkt.\n", Spielername);
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, ++spieler_sieg, comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}

			}
			else if(input == "Papier")
			{
				if((input == "Papier") & (variablen[index] == "Papier"))
			{
				Console.WriteLine("Unentschieden! Beide erhalten einen Punkt.\n");
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, ++spieler_sieg, ++comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
				else if((input == "Papier") & (variablen[index] == "Schere"))
			{
				Console.WriteLine("Du verlierst! Computer erhält einen Punkt.\n");
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, spieler_sieg, ++comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}
				else if((input == "Papier") & (variablen[index] == "Stein"))
			{
				Console.WriteLine("Du gewinnst! {0} erhält einen Punkt.\n", Spielername);
				Console.WriteLine("Neuer Spielstand: {0}: {1}, Computer: {2}.", Spielername, ++spieler_sieg, comp_sieg);
				Console.ReadLine();
				goto spielbeginn;
			}

			}
			else
				Console.WriteLine("Ungültige Eingabe - Versuch es noch einmal!");
				Console.ReadLine();
				goto spielbeginn;


			}
			
	}
		
		}
	
