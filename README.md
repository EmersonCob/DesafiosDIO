# DesafiosDIO
Resolvendo os desafios DIO


# Calculando Imposto de Renda
  
  
  
        let calc = window.prompt(""); // Substituir por: let calc = gets();

        if (calc<=2000){
        window.alert('Isento'); ('Isento'); console.log('Isento');
        } else if (calc<=3000) {
        sFaixa = (calc - 2000)*0.08;
        result = (sFaixa);
        result = result.toFixed(2);
        window.alert('R$ ' + result); // Substituir por console.log('R$ ' + result);
        } else if (calc<=4500) {
            aux1 = calc - 2000;
            aux2 = calc - 3000;
            aux2 = aux2>=0 ? aux2 : 0;
            sFaixa = ((calc - 2000)-aux2)* 0.08;
            tFaixa = (calc - 3000) * 0.18;
            result = (sFaixa+tFaixa);
            result = result.toFixed(2);
            window.alert('R$ ' + result); // Substituir por console.log('R$ ' + result);
        } else {
            aux1 = calc - 2000;
            aux2 = calc - 3000;
            aux3 = calc - 4500;
            aux2 = aux2>=0 ? aux2 : 0;
            aux3 = aux3>=0 ? aux3 : 0;
            sFaixa = ((calc - 2000)-aux2)* 0.08;
            tFaixa = ((calc - 3000)-aux3) * 0.18;
            qFaixa =  (calc-4500) * 0.28;
            result = (sFaixa+tFaixa+qFaixa);
            result = result.toFixed(2);
            window.alert('R$ ' + result); // Substituir por console.log('R$ ' + result);
            
            
