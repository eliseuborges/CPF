<?php
/**
 * @author Eliseu Borges do Amaral
 */
class CPF{
	
	private $CPF;
	
	public function __construct($CPF)
	{
		$this->CPF = $CPF;
	}
	
	/**
	 * Retorna a UF que o CPF foi registrado
	 * Regra extraida de https://www.geradordecpf.org/
	 */
	public function getUFRegistro()
	{
		$nonoDigito = substr($this->CPF, 8, 1);
		
		switch($nonoDigito)
		{
			case 0: return "Rio Grande do Sul"; break;
			case 1: return "Distrito Federal, Goiás, Mato Grosso do Sul e Tocantins"; break;
			case 2: return "Pará, Amazonas, Acre, Amapá, Rondônia e Roraima"; break;
			case 3: return "Ceará, Maranhão e Piauí"; break;
			case 4: return "Pernambuco, Rio Grande do Norte, Paraíba e Alagoas"; break;
			case 5: return "Bahia e Sergipe"; break;
			case 6: return "Minas Gerais"; break;
			case 7: return "Rio de Janeiro e Espírito Santo"; break;
			case 8: return "São Paulo"; break;
			case 9: return "Paraná e Santa Catarina"; break;
		}
	}
}
