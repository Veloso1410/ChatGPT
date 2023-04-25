public class a {
	public static void main(String[] args) {
		Scanner leitor = new Scanner(System.in);
		
		System.out.println("Deseja pedir uma pizza doce, salgada ou mista? ");
		String docesal = leitor.next();
		
		double preço = 0;
		String pedido = "";
		
		// PIZZA DOCE
		if (docesal.equals("doce") || docesal.equals("Doce")) {
			System.out.println("Tamanhos disponíveis: ");
			System.out.println("Pequena (R$32,00)");
			System.out.println("Média (R$43,00)");
			System.out.println("Grande (R$50,00)");
			System.out.println("Digite o tamanho da pizza: ");
			String tamanho = leitor.next();
			
			while (!tamanho.equals("pequena") && !tamanho.equals("Pequena") && !tamanho.equals("média") && !tamanho.equals("Média") && !tamanho.equals("media") && !tamanho.equals("media") && !tamanho.equals("grande") && !tamanho.equals("Grande")) {
				System.out.println("Tamanhos disponíveis: ");
				System.out.println("Pequena (R$28,00)");
				System.out.println("Média (R$36,00)");
				System.out.println("Grande (R$45,00)");
				System.out.println("Por favor, digite um tamanho válido: ");
				tamanho = leitor.next();
			}
			
			if (tamanho.equals("pequena") || tamanho.equals("Pequena")) {
				preço =+ 32;
			}
			if (tamanho.equals("média") || tamanho.equals("Média") || tamanho.equals("media") || tamanho.equals("Media")) {
				preço =+ 40;
			}
			if (tamanho.equals("Grande") || tamanho.equals("grande")) {
				preço =+ 50;
			}
			
			System.out.println("Sabores disponíveis: ");
			System.out.println("Banana com Chocolate");
			System.out.println("Banana e Canela");
			System.out.println("Chocolate");
			System.out.println("Chocolate Branco");
			System.out.println("Digite o sabor da pizza: ");
			String m1 = leitor.next();
			
			while (!m1.equals("Banana com Chocolate") && !m1.equals("Banana com chocolate") && !m1.equals("banana com chocolate") && !m1.equals("Banana com Canela") && !m1.equals("Banana com canela") && !m1.equals("banana com canela") && !m1.equals("Chocolate") && !m1.equals("chocolate") && !m1.equals("Chocolate Branco") && !m1.equals("Chocolate branco") && !m1.equals("chocolate branco")) {
				System.out.println("Digite um sabor válido: ");
				m1 = leitor.next();
				}
			
			pedido += m1 + " " + tamanho + " " + "(" + preço + ")";
		// PIZZA SALGADA	
		}
		if (docesal.equals("Salgada") || docesal.equals("salgada")) {
		System.out.println("Tamanhos disponíveis: ");
		System.out.println("Pequena (R$28,00)");
		System.out.println("Média (R$36,00)");
		System.out.println("Grande (R$45,00)");
		System.out.println("Digite o tamanho da pizza: ");
		String tamanho = leitor.next();

		while (!tamanho.equals("pequena") && !tamanho.equals("Pequena") && !tamanho.equals("média") && !tamanho.equals("Média") && !tamanho.equals("media") && !tamanho.equals("media") && !tamanho.equals("grande") && !tamanho.equals("Grande")) {
			System.out.println("Tamanhos disponíveis: ");
			System.out.println("Pequena (R$28,00)");
			System.out.println("Média (R$36,00)");
			System.out.println("Grande (R$45,00)");
			System.out.println("Por favor, digite um tamanho válido: ");
			tamanho = leitor.next();
		}
		if (tamanho.equals("pequena") || tamanho.equals("Pequena")) {
			preço =+ 28;
		}
		if (tamanho.equals("média") || tamanho.equals("Média") || tamanho.equals("media") || tamanho.equals("Media")) {
			preço =+ 36;
		}
		if (tamanho.equals("Grande") || tamanho.equals("grande")) {
			preço =+ 45;
		}
		System.out.println("Sabores disponíveis: ");
		System.out.println("Portuguesa (R$28,00)");
		System.out.println("Calabresa (R$36,00)");
		System.out.println("4 Queijos (R$45,00)");
		System.out.println("Carne Seca (R$45,00)");
		System.out.println("Digite o sabor da pizza: ");
		String m1 = leitor.next();
		
		while (!m1.equals("Portuguesa") && !m1.equals("portuguesa") && !m1.equals("Calabresa") && !m1.equals("calabresa") && !m1.equals("4 queijos") && !m1.equals("4 Queijos") && !m1.equals("Carne Seca") && !m1.equals("Carne seca") && !m1.equals("carne seca") && !m1.equals("carne Seca")) {
			System.out.println("Digite um sabor válido: ");
			m1 = leitor.next();
			}
		
		pedido += m1 + " " + tamanho  + " " + "(" + preço + ")";
		}
		
		
		// PIZZA MISTA
		if (docesal.equals("Mista") || docesal.equals("mista")) {
			System.out.println("Tamanhos disponíveis: ");
			System.out.println("Pequena");
			System.out.println("Média");
			System.out.println("Grande");
			System.out.println("Digite o tamanho da pizza: ");
			String tamanho = leitor.next();
			
			while (!tamanho.equals("pequena") && !tamanho.equals("Pequena") && !tamanho.equals("média") && !tamanho.equals("Média") && !tamanho.equals("media") && !tamanho.equals("media") && !tamanho.equals("grande") && !tamanho.equals("Grande")) {
				System.out.println("Tamanhos disponíveis: ");
				System.out.println("Pequena");
				System.out.println("Média");
				System.out.println("Grande");
				System.out.println("Por favor, digite um tamanho válido: ");
				tamanho = leitor.next();
			}
			
			if (tamanho.equals("pequena") || tamanho.equals("Pequena")) {
				System.out.println("(O preço da pizza é dado pela soma dos preços de ambas as partes) ");
			
			System.out.println("Sabores salgados disponíveis: ");
			System.out.println("Portuguesa (R$14,00)");
			System.out.println("Calabresa (R$14,00)");
			System.out.println("4 Queijos (R$14,00)");
			System.out.println("Carne Seca (R$14,00)");
			System.out.println("Sabores doces disponíveis: ");
			System.out.println("Banana com Chocolate (R$16,00)");
			System.out.println("Banana e Canela (R$16,00)");
			System.out.println("Chocolate (R$16,00)");
			System.out.println("Chocolate Branco (R$16,00)");
			
			System.out.println("Digite a opção da primeira metade da pizza: ");
			String m1 = leitor.next();
			
			if (m1.equals("Portuguesa") || m1.equals("portuguesa") || m1.equals("Calabresa") || m1.equals("calabresa") || m1.equals("4 queijos") || m1.equals("4 Queijos") || m1.equals("Carne Seca") || m1.equals("Carne seca") || m1.equals("carne seca") || m1.equals("carne Seca")) {
			preço =+ 14;
			}
			if (m1.equals("Banana com Chocolate") || m1.equals("Banana com chocolate") || m1.equals("banana com chocolate") || m1.equals("Banana com Canela") || m1.equals("Banana com canela") || m1.equals("banana com canela") || m1.equals("Chocolate") || m1.equals("chocolate") || m1.equals("Chocolate Branco") || m1.equals("Chocolate branco") || m1.equals("chocolate branco")) {
			preço =+ 16;
			}
			
			while (!m1.equals("Portuguesa") && !m1.equals("portuguesa") && !m1.equals("Calabresa") && !m1.equals("calabresa") && !m1.equals("4 queijos") && !m1.equals("4 Queijos") && !m1.equals("Carne Seca") && !m1.equals("Carne seca") && !m1.equals("carne seca") && !m1.equals("carne Seca") && !m1.equals("Banana com Chocolate") && !m1.equals("Banana com chocolate") && !m1.equals("banana com chocolate") && !m1.equals("Banana com Canela") && !m1.equals("Banana com canela") && !m1.equals("banana com canela") && !m1.equals("Chocolate") && !m1.equals("chocolate") && !m1.equals("Chocolate Branco") && !m1.equals("Chocolate branco") && !m1.equals("chocolate branco")) {
			System.out.println("Digite um sabor válido: ");
			m1 = leitor.next();
			}
			
			System.out.println("Digite a opção da segunda metade da pizza: ");
			String m2 = leitor.next();
			
			if (m2.equals("Portuguesa") || m2.equals("portuguesa") || m2.equals("Calabresa") || m2.equals("calabresa") || m2.equals("4 queijos") || m2.equals("4 Queijos") || m2.equals("Carne Seca") || m2.equals("Carne seca") || m2.equals("carne seca") || m2.equals("carne Seca")) {
				preço =+ 14;
				}
				if (m2.equals("Banana com Chocolate") || m2.equals("Banana com chocolate") || m2.equals("banana com chocolate") || m2.equals("Banana com Canela") || m2.equals("Banana com canela") || m2.equals("banana com canela") || m2.equals("Chocolate") || m2.equals("chocolate") || m2.equals("Chocolate Branco") || m2.equals("Chocolate branco") || m2.equals("chocolate branco")) {
				preço =+ 16;
				}
				
				while (!m2.equals("Portuguesa") && !m2.equals("portuguesa") && !m2.equals("Calabresa") && !m2.equals("calabresa") && !m2.equals("4 queijos") && !m2.equals("4 Queijos") && !m2.equals("Carne Seca") && !m2.equals("Carne seca") && !m2.equals("carne seca") && !m2.equals("carne Seca") && !m2.equals("Banana com Chocolate") && !m2.equals("Banana com chocolate") && !m2.equals("banana com chocolate") && !m2.equals("Banana com Canela") && !m2.equals("Banana com canela") && !m2.equals("banana com canela") && !m2.equals("Chocolate") && !m2.equals("chocolate") && !m2.equals("Chocolate Branco") && !m2.equals("Chocolate branco") && !m2.equals("chocolate branco")) {
				System.out.println("Digite um sabor válido: ");
				m2 = leitor.next();
				}
				pedido += "metade" + m1 + ", metade " + m2 + " " + "(" + preço + ")";
				}
		
			if (tamanho.equals("média") || tamanho.equals("Média") || tamanho.equals("media") || tamanho.equals("Media")) {
				System.out.println("(O preço da pizza é dado pela soma dos preços de ambas as partes) ");
			
			System.out.println("Sabores salgados disponíveis: ");
			System.out.println("Portuguesa (R$18,00)");
			System.out.println("Calabresa (R$18,00)");
			System.out.println("4 Queijos (R$18,00)");
			System.out.println("Carne Seca (R$18,00)");
			System.out.println("Sabores doces disponíveis: ");
			System.out.println("Banana com Chocolate (R$21,50)");
			System.out.println("Banana e Canela (R$21,50)");
			System.out.println("Chocolate (R$21,50)");
			System.out.println("Chocolate Branco (R$21,50)");
			
			System.out.println("Digite a opção da primeira metade da pizza: ");
			String m1 = leitor.next();
			
			if (m1.equals("Portuguesa") || m1.equals("portuguesa") || m1.equals("Calabresa") || m1.equals("calabresa") || m1.equals("4 queijos") || m1.equals("4 Queijos") || m1.equals("Carne Seca") || m1.equals("Carne seca") || m1.equals("carne seca") || m1.equals("carne Seca")) {
			preço =+ 18;
			}
			if (m1.equals("Banana com Chocolate") || m1.equals("Banana com chocolate") || m1.equals("banana com chocolate") || m1.equals("Banana com Canela") || m1.equals("Banana com canela") || m1.equals("banana com canela") || m1.equals("Chocolate") || m1.equals("chocolate") || m1.equals("Chocolate Branco") || m1.equals("Chocolate branco") || m1.equals("chocolate branco")) {
			preço =+ 21.5;
			}
			
			while (!m1.equals("Portuguesa") && !m1.equals("portuguesa") && !m1.equals("Calabresa") && !m1.equals("calabresa") && !m1.equals("4 queijos") && !m1.equals("4 Queijos") && !m1.equals("Carne Seca") && !m1.equals("Carne seca") && !m1.equals("carne seca") && !m1.equals("carne Seca") && !m1.equals("Banana com Chocolate") && !m1.equals("Banana com chocolate") && !m1.equals("banana com chocolate") && !m1.equals("Banana com Canela") && !m1.equals("Banana com canela") && !m1.equals("banana com canela") && !m1.equals("Chocolate") && !m1.equals("chocolate") && !m1.equals("Chocolate Branco") && !m1.equals("Chocolate branco") && !m1.equals("chocolate branco")) {
			System.out.println("Digite um sabor válido: ");
			m1 = leitor.next();
			}
			
			System.out.println("Digite a opção da segunda metade da pizza: ");
			String m2 = leitor.next();
			
			if (m2.equals("Portuguesa") || m2.equals("portuguesa") || m2.equals("Calabresa") || m2.equals("calabresa") || m2.equals("4 queijos") || m2.equals("4 Queijos") || m2.equals("Carne Seca") || m2.equals("Carne seca") || m2.equals("carne seca") || m2.equals("carne Seca")) {
				preço =+ 18;
				}
				if (m2.equals("Banana com Chocolate") || m2.equals("Banana com chocolate") || m2.equals("banana com chocolate") || m2.equals("Banana com Canela") || m2.equals("Banana com canela") || m2.equals("banana com canela") || m2.equals("Chocolate") || m2.equals("chocolate") || m2.equals("Chocolate Branco") || m2.equals("Chocolate branco") || m2.equals("chocolate branco")) {
				preço =+ 21.5;
				}
				
				while (!m2.equals("Portuguesa") && !m2.equals("portuguesa") && !m2.equals("Calabresa") && !m2.equals("calabresa") && !m2.equals("4 queijos") && !m2.equals("4 Queijos") && !m2.equals("Carne Seca") && !m2.equals("Carne seca") && !m2.equals("carne seca") && !m2.equals("carne Seca") && !m2.equals("Banana com Chocolate") && !m2.equals("Banana com chocolate") && !m2.equals("banana com chocolate") && !m2.equals("Banana com Canela") && !m2.equals("Banana com canela") && !m2.equals("banana com canela") && !m2.equals("Chocolate") && !m2.equals("chocolate") && !m2.equals("Chocolate Branco") && !m2.equals("Chocolate branco") && !m2.equals("chocolate branco")) {
				System.out.println("Digite um sabor válido: ");
				m2 = leitor.next();
				}
				pedido += "metade" + m1 + ", metade " + m2 + " " + "(" + preço + ")";
			}
			if (tamanho.equals("Grande") || tamanho.equals("grande")) {
				System.out.println("(O preço da pizza é dado pela soma dos preços de ambas as partes) ");
			
			System.out.println("Sabores salgados disponíveis: ");
			System.out.println("Portuguesa (R$22,50)");
			System.out.println("Calabresa (R$22,50)");
			System.out.println("4 Queijos (R$22,50)");
			System.out.println("Carne Seca (R$22,50)");
			System.out.println("Sabores doces disponíveis: ");
			System.out.println("Banana com Chocolate (R$25,00)");
			System.out.println("Banana e Canela (R$25,00)");
			System.out.println("Chocolate (R$25,00)");
			System.out.println("Chocolate Branco (R$25,00)");
			
			System.out.println("Digite a opção da primeira metade da pizza: ");
			String m1 = leitor.next();
			
			if (m1.equals("Portuguesa") || m1.equals("portuguesa") || m1.equals("Calabresa") || m1.equals("calabresa") || m1.equals("4 queijos") || m1.equals("4 Queijos") || m1.equals("Carne Seca") || m1.equals("Carne seca") || m1.equals("carne seca") || m1.equals("carne Seca")) {
			preço = preço + 22.5;
			}
			if (m1.equals("Banana com Chocolate") || m1.equals("Banana com chocolate") || m1.equals("banana com chocolate") || m1.equals("Banana com Canela") || m1.equals("Banana com canela") || m1.equals("banana com canela") || m1.equals("Chocolate") || m1.equals("chocolate") || m1.equals("Chocolate Branco") || m1.equals("Chocolate branco") || m1.equals("chocolate branco")) {
			preço = preço +  25;
			}
			
			while (!m1.equals("Portuguesa") && !m1.equals("portuguesa") && !m1.equals("Calabresa") && !m1.equals("calabresa") && !m1.equals("4 queijos") && !m1.equals("4 Queijos") && !m1.equals("Carne Seca") && !m1.equals("Carne seca") && !m1.equals("carne seca") && !m1.equals("carne Seca") && !m1.equals("Banana com Chocolate") && !m1.equals("Banana com chocolate") && !m1.equals("banana com chocolate") && !m1.equals("Banana com Canela") && !m1.equals("Banana com canela") && !m1.equals("banana com canela") && !m1.equals("Chocolate") && !m1.equals("chocolate") && !m1.equals("Chocolate Branco") && !m1.equals("Chocolate branco") && !m1.equals("chocolate branco")) {
			System.out.println("Digite um sabor válido: ");
			m1 = leitor.next();
			}
			
			System.out.println("Digite a opção da segunda metade da pizza: ");
			String m2 = leitor.next();
			
			if (m2.equals("Portuguesa") || m2.equals("portuguesa") || m2.equals("Calabresa") || m2.equals("calabresa") || m2.equals("4 queijos") || m2.equals("4 Queijos") || m2.equals("Carne Seca") || m2.equals("Carne seca") || m2.equals("carne seca") || m2.equals("carne Seca")) {
				preço = preço + 22.5;
				}
			if (m2.equals("Banana com Chocolate") || m2.equals("Banana com chocolate") || m2.equals("banana com chocolate") || m2.equals("Banana com Canela") || m2.equals("Banana com canela") || m2.equals("banana com canela") || m2.equals("Chocolate") || m2.equals("chocolate") || m2.equals("Chocolate Branco") || m2.equals("Chocolate branco") || m2.equals("chocolate branco")) {
				preço = preço + 25;
				}
				
				while (!m2.equals("Portuguesa") && !m2.equals("portuguesa") && !m2.equals("Calabresa") && !m2.equals("calabresa") && !m2.equals("4 queijos") && !m2.equals("4 Queijos") && !m2.equals("Carne Seca") && !m2.equals("Carne seca") && !m2.equals("carne seca") && !m2.equals("carne Seca") && !m2.equals("Banana com Chocolate") && !m2.equals("Banana com chocolate") && !m2.equals("banana com chocolate") && !m2.equals("Banana com Canela") && !m2.equals("Banana com canela") && !m2.equals("banana com canela") && !m2.equals("Chocolate") && !m2.equals("chocolate") && !m2.equals("Chocolate Branco") && !m2.equals("Chocolate branco") && !m2.equals("chocolate branco")) {
				System.out.println("Digite um sabor válido: ");
				m2 = leitor.next();
				}
				pedido += "metade " + m1 + ", metade " + m2 + " " + "(" + preço + ")";
			}
			}
		leitor.close();
			System.out.println(pedido);
			
		
		}
}
