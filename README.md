<div align="center">

## convert peso to word


</div>

### Description

convert peso to word
 
### More Info
 
Input Peso Amount

"This Program Accept Up to 100,000 Pesos Only

"This Program Accept Up to 100,000 Pesos Only"


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[MICHAEL ESPIRITU](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/michael-espiritu.md)
**Level**          |Beginner
**User Rating**    |2.6 (13 globes from 5 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__3-32.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/michael-espiritu-convert-peso-to-word__3-11270/archive/master.zip)

### API Declarations

# include &lt;iostream.h&gt;


### Source Code

```
//Coded by Michael L Espiritu //
# include <iostream.h>
int main()
{
  int tmpDollar,tmpPound,tmpFranc,tmpDinar,tmpRial,tmpRupial,tmpBaht,tmpDirham,tmpEuro;
	int passnum,num;
	int tmpAmounttoConvert;
  int passnumber;
	float origvalue;
	float passcent;
	int Thousand,Hundred1,Hundred2,Hundred3,Fifty,Twenty,Ten;
	int Five,One,TwentyFivecent,Tencent,Fivecent;
  cout << "This Program Accept Up to 100,000 Pesos Only !\n\n";
	cout  << "Input Amount of Peso: " << "" ;
  cin >> num;
  cout << "\n\nAmount of Peso in Word: \n\n\t";
  tmpAmounttoConvert=num;
	passnum= num; //pass the value of inputted number into whole
	//1000 thousand
	passnum=passnum/1000;
	 if (passnum==0)
		{
			passnum=num;
		}
	 else
		{
		   num=num-(passnum*1000);
		   if(num==0)
			 {
				  switch(passnum)
						{
					case 1: cout << "One Thousand Pesos"; break;
					case 2: cout << "Two Thousand Pesos"; break;
					case 3: cout << "Three Thousand Pesos"; break;
					case 4: cout << "Four Thousand Pesos"; break;
					case 5: cout << "Five Thousand Pesos"; break;
					case 6: cout << "Six Thousand Pesos"; break;
					case 7: cout << "Seven Thousand Pesos"; break;
					case 8: cout << "Eight Thousand Pesos"; break;
					case 9: cout << "Nine Thousand Pesos"; break;
					case 10: cout << "Ten Thousand Pesos"; break;
					case 11: cout << "Eleven Thousand Pesos"; break;
					case 12: cout << "Twelve Thousand Pesos"; break;
					case 13: cout << "thirteen Thousand Pesos"; break;
					case 14: cout << "Fourteen Thousand Pesos"; break;
					case 15: cout << "FifteenT housand Pesos"; break;
					case 16: cout << "Sixteen Thousand Pesos"; break;
					case 17: cout << "Seventen Thousand Pesos"; break;
					case 18: cout << "Eighteen Thousand Pesos"; break;
					case 19: cout << "Nineteen Thousand Pesos"; break;
					case 20: cout << "FTwenty Thousand Pesos"; break;
					case 21: cout << "Twenty One Thousand Pesos"; break;
					case 22: cout << "Twenty Two Thousand Pesos"; break;
					case 23: cout << "Twenty Three Thousand Pesos"; break;
					case 24: cout << "Twenty Four Thousand Pesos"; break;
					case 25: cout << "Twenty Five Thousand Pesos"; break;
					case 26: cout << "Twenty Six Thousand Pesos"; break;
					case 27: cout << "Twenty Seven Thousand Pesos"; break;
					case 28: cout << "Twenty Eight Thousand Pesos"; break;
					case 29: cout << "Twenty Nine Thousand Pesos"; break;
					case 30: cout << "Thirty Thousand Pesos"; break;
					case 31: cout << "Thirty One Thousand Pesos"; break;
					case 32: cout << "Thirty Two Thousand Pesos"; break;
					case 33: cout << "Thirty Three Thousand Pesos"; break;
					case 34: cout << "Thirty Four Thousand Pesos"; break;
					case 35: cout << "Thirty Five Thousand Pesos"; break;
					case 36: cout << "Thirty Six Thousand Pesos"; break;
					case 37: cout << "Thirty Seven Thousand Pesos"; break;
					case 38: cout << "Thirty Eight Thousand Pesos"; break;
					case 39: cout << "Thirty Nine Thousand Pesos"; break;
					case 40: cout << "Fourty Pesos Thousand"; break;
					case 41: cout << "Fourty One Thousand Pesos"; break;
					case 42: cout << "Fourty Two Thousand Three Pesos"; break;
					case 43: cout << "Fourty Three Thousand Pesos"; break;
					case 44: cout << "Fourty Four Thousand Pesos"; break;
					case 45: cout << "Fourty Five Thousand Pesos"; break;
					case 46: cout << "Fourty Six Thousand Pesos"; break;
					case 47: cout << "Fourty Seven Thousand Pesos"; break;
					case 48: cout << "Fourty Eight Thousand Pesos";break;
					case 49: cout << "Fourty Nine Thousand Pesos"; break;
					case 50: cout << "Fifty Thousand Pesos"; break;
					case 51: cout << "Fifty One Thousand Pesos"; break;
					case 52: cout << "Fifty Two Thousand Pesos"; break;
					case 53: cout << "Fifty Three Thousand Pesos";break;
					case 54: cout << "Fifty Four Thousand Pesos"; break;
					case 55: cout << "Fifty Five Thousand Pesos"; break;
					case 56: cout << "Fifty Six Thousand Pesos"; break;
					case 57: cout << "Fifty Seven Thousand Pesos"; break;
					case 58: cout << "Fifty Eight Thousand Pesos"; break;
					case 59: cout << "Fifty Nine Thousand Pesos"; break;
					case 60: cout << "Sixty Thousand Pesos"; break;
					case 61: cout << "Sixty One Thousand Pesos"; break;
					case 62: cout << "Sixty Four Thousand Pesos"; break;
					case 63: cout << "Sixty Three Thousand Pesos";break;
					case 64: cout << "Sixty Four Thousand Pesos"; break;
					case 65: cout << "Sixty Five Thousand Pesos"; break;
					case 66: cout << "Sixty Six Thousand Pesos"; break;
					case 67: cout << "Sixty Seven Thousand Pesos"; break;
					case 68: cout << "Sixty Eight Thousand Pesos"; break;
					case 69: cout << "Sixty Nine Thousand Pesos"; break;
					case 70: cout << "Seventy Thousand Pesos"; break;
					case 71: cout << "Seventy One Thousand Pesos"; break;
					case 72: cout << "Seventy Four Thousand Pesos"; break;
					case 73: cout << "Seventy Three Thousand Pesos";break;
					case 74: cout << "Seventy Four Thousand Pesos"; break;
					case 75: cout << "Seventy Five Thousand Pesos"; break;
					case 76: cout << "Seventy Six Thousand Pesos"; break;
					case 77: cout << "Seventy Seven Thousand Pesos"; break;
					case 78: cout << "Seventy Eight Thousand Pesos"; break;
					case 79: cout << "Seventy Nine Thousand Pesos"; break;
					case 80: cout << "Eighty Thousand Pesos"; break;
					case 81: cout << "Eighty One Thousand Pesos"; break;
					case 82: cout << "Eighty Four Thousand Pesos"; break;
					case 83: cout << "Eighty Three Thousand Pesos";break;
					case 84: cout << "Eighty Four Thousand Pesos"; break;
          case 85: cout << "Eighty Six Thousand Pesos"; break;
					case 86: cout << "Eighty Five Thousand Pesos"; break;
					case 87: cout << "Eighty Seven Thousand Pesos"; break;
					case 88: cout << "Eighty Eight Thousand Pesos"; break;
					case 89: cout << "Eighty Nine Thousand Pesos"; break;
					case 90: cout << "Ninety Thousand Pesos"; break;
					case 91: cout << "Ninety One Thousand Pesos"; break;
					case 92: cout << "Ninety Four Thousand Pesos"; break;
					case 93: cout << "Ninety Three Thousand Pesos";break;
					case 94: cout << "Ninety Four Thousand Pesos"; break;
          case 95: cout << "Ninety Five Thousand Pesos"; break;
					case 96: cout << "Ninety Six Thousand Pesos"; break;
					case 97: cout << "Ninety Seven Thousand Pesos"; break;
					case 98: cout << "Ninety Eight Thousand Pesos"; break;
					case 99: cout << "Ninety Nine Thousand Pesos"; break;
					case 100: cout << "One Hundred Thousand Pesos"; break;					}
			 }
			 else
			 {
						switch(passnum)
						{
						case 1: cout << "One Thousand "; break;
					case 2: cout << "Two Thousand "; break;
					case 3: cout << "Three Thousand "; break;
					case 4: cout << "Four Thousand "; break;
					case 5: cout << "Five Thousand "; break;
					case 6: cout << "Six Thousand "; break;
					case 7: cout << "Seven Thousand "; break;
					case 8: cout << "Eight Thousand "; break;
					case 9: cout << "Nine Thousand "; break;
					case 10: cout << "Ten Thousand "; break;
					case 11: cout << "Eleven Thousand "; break;
					case 12: cout << "Twelve Thousand "; break;
					case 13: cout << "thirteen Thousand "; break;
					case 14: cout << "Fourteen Thousand "; break;
					case 15: cout << "FifteenT housand "; break;
					case 16: cout << "Sixteen Thousand "; break;
					case 17: cout << "Seventen Thousand "; break;
					case 18: cout << "Eighteen Thousand "; break;
					case 19: cout << "Nineteen Thousand "; break;
					case 20: cout << "Twenty Thousand "; break;
					case 21: cout << "Twenty One Thousand "; break;
					case 22: cout << "Twenty Two Thousand "; break;
					case 23: cout << "Twenty Three Thousand "; break;
					case 24: cout << "Twenty Four Thousand "; break;
					case 25: cout << "Twenty Five Thousand "; break;
					case 26: cout << "Twenty Six Thousand "; break;
					case 27: cout << "Twenty Seven Thousand "; break;
					case 28: cout << "Twenty Eight Thousand "; break;
					case 29: cout << "Twenty Nine Thousand "; break;
					case 30: cout << "Thirty Thousand "; break;
					case 31: cout << "Thirty One Thousand "; break;
					case 32: cout << "Thirty Two Thousand "; break;
					case 33: cout << "Thirty Three Thousand "; break;
					case 34: cout << "Thirty Four Thousand "; break;
					case 35: cout << "Thirty Five Thousand "; break;
					case 36: cout << "Thirty Six Thousand "; break;
					case 37: cout << "Thirty Seven Thousand "; break;
					case 38: cout << "Thirty Eight Thousand "; break;
					case 39: cout << "Thirty Nine Thousand "; break;
					case 40: cout << "Fourty Pesos Thousand "; break;
					case 41: cout << "Fourty One Thousand "; break;
					case 42: cout << "Fourty Two Thousand Three "; break;
					case 43: cout << "Fourty Three Thousand "; break;
					case 44: cout << "Fourty Four Thousand "; break;
					case 45: cout << "Fourty Five Thousand "; break;
					case 46: cout << "Fourty Six Thousand "; break;
					case 47: cout << "Fourty Seven Thousand "; break;
					case 48: cout << "Fourty Eight Thousand ";break;
					case 49: cout << "Fourty Nine Thousand "; break;
					case 50: cout << "Fifty Thousand Pesos"; break;
					case 51: cout << "Fifty One Thousand "; break;
					case 52: cout << "Fifty Two Thousand "; break;
					case 53: cout << "Fifty Three Thousand ";break;
					case 54: cout << "Fifty Four Thousand "; break;
					case 55: cout << "Fifty Five Thousand "; break;
					case 56: cout << "Fifty Six Thousand "; break;
					case 57: cout << "Fifty Seven Thousand "; break;
					case 58: cout << "Fifty Eight Thousand "; break;
					case 59: cout << "Fifty Nine Thousand "; break;
					case 60: cout << "Sixty Thousand Pesos"; break;
					case 61: cout << "Sixty One Thousand "; break;
					case 62: cout << "Sixty Four Thousand "; break;
					case 63: cout << "Sixty Three Thousand ";break;
					case 64: cout << "Sixty Four Thousand "; break;
					case 65: cout << "Sixty Five Thousand "; break;
					case 66: cout << "Sixty Six Thousand "; break;
					case 67: cout << "Sixty Seven Thousand "; break;
					case 68: cout << "Sixty Eight Thousand "; break;
					case 69: cout << "Sixty Nine Thousand "; break;
					case 70: cout << "Seventy Thousand "; break;
					case 71: cout << "Seventy One Thousand "; break;
					case 72: cout << "Seventy Four Thousand "; break;
					case 73: cout << "Seventy Three Thousand ";break;
					case 74: cout << "Seventy Four Thousand "; break;
					case 75: cout << "Seventy Five Thousand "; break;
					case 76: cout << "Seventy Six Thousand "; break;
					case 77: cout << "Seventy Seven Thousand "; break;
					case 78: cout << "Seventy Eight Thousand "; break;
					case 79: cout << "Seventy Nine Thousand "; break;
					case 80: cout << "Eighty Thousand Pesos"; break;
					case 81: cout << "Eighty One Thousand "; break;
					case 82: cout << "Eighty Four Thousand "; break;
					case 83: cout << "Eighty Three Thousand ";break;
					case 84: cout << "Eighty Four Thousand "; break;
          case 85: cout << "Eighty Six Thousand "; break;
					case 86: cout << "Eighty Five Thousand "; break;
					case 87: cout << "Eighty Seven Thousand "; break;
					case 88: cout << "Eighty Eight Thousand "; break;
					case 89: cout << "Eighty Nine Thousand "; break;
					case 90: cout << "Ninety Thousand "; break;
					case 91: cout << "Ninety One Thousand "; break;
					case 92: cout << "Ninety Four Thousand "; break;
					case 93: cout << "Ninety Three Thousand ";break;
					case 94: cout << "Ninety Four Thousand "; break;
          case 95: cout << "Ninety Five Thousand "; break;
					case 96: cout << "Ninety Six Thousand "; break;
					case 97: cout << "Ninety Seven Thousand "; break;
					case 98: cout << "Ninety Eight Thousand "; break;
					case 99: cout << "Ninety Nine Thousand "; break;
					case 100: cout << "One Hundred Thousand "; break;
						}
			 }
      //Pass Decremented Value
			passnum=num;
		}
	  //100 hundred
	 passnum=passnum/100;
	 if (passnum==0)
		{
			passnum=num;
		}
	 else
		{
		  num= num- (passnum*100);
			 if(num==0)
			 {
				  switch(passnum)
						{
							case 1: cout << "One Hundred Pesos ";break;
							case 2: cout << "Two Hundred Pesos ";break;
							case 3: cout << "Three Hundred Pesos ";break;
							case 4: cout << "Four Hundred Pesos ";break;
							case 5: cout << "Five Hundred Pesos ";break;
							case 6: cout << "Six Hundred Pesos ";break;
							case 7: cout << "Seven Hundred Pesos ";break;
							case 8: cout << "Eight Hundred Pesos ";break;
							case 9: cout << "Nine Hundred Pesos ";break;
						}
			 }
			 else
			 {
						switch(passnum)
						{
							case 1: cout << "One Hundred ";break;
							case 2: cout << "Two Hundred ";break;
							case 3: cout << "Three Hundred ";break;
							case 4: cout << "Four Hundred ";break;
							case 5: cout << "Five Hundred ";break;
							case 6: cout << "Six Hundred ";break;
							case 7: cout << "Seven Hundred ";break;
							case 8: cout << "Eight Hundred ";break;
							case 9: cout << "Nine Hundred ";break;
						}
			 }
			passnum=num;
		}
	 //One Pesos
	 passnum=passnum/1;
	    switch(passnum)
				{
					case 1: cout << "One Pesos"; break;
					case 2: cout << "Two Pesos"; break;
					case 3: cout << "Three Pesos"; break;
					case 4: cout << "Four Pesos"; break;
					case 5: cout << "Five Pesos"; break;
					case 6: cout << "Six Pesos"; break;
					case 7: cout << "Seven Pesos"; break;
					case 8: cout << "Eight Pesos"; break;
					case 9: cout << "Nine Pesos"; break;
					case 10: cout << "Ten Pesos"; break;
					case 11: cout << "Eleven Pesos"; break;
					case 12: cout << "Twelve Pesos"; break;
					case 13: cout << "thirteen Pesos"; break;
					case 14: cout << "Fourteen Pesos"; break;
					case 15: cout << "Fifteen Pesos"; break;
					case 16: cout << "Sixteen Pesos"; break;
					case 17: cout << "Seventen Pesos"; break;
					case 18: cout << "Eighteen Pesos"; break;
					case 19: cout << "Nineteen Pesos"; break;
					case 20: cout << "FTwenty Pesos"; break;
					case 21: cout << "Twenty One Pesos"; break;
					case 22: cout << "Twenty Two Pesos"; break;
					case 23: cout << "Twenty Three Pesos"; break;
					case 24: cout << "Twenty Four Pesos"; break;
					case 25: cout << "Twenty Five Pesos"; break;
					case 26: cout << "Twenty Six Pesos"; break;
					case 27: cout << "Twenty Seven Pesos"; break;
					case 28: cout << "Twenty Eight Pesos"; break;
					case 29: cout << "Twenty Nine Pesos"; break;
					case 30: cout << "Thirty Pesos"; break;
					case 31: cout << "Thirty One Pesos"; break;
					case 32: cout << "Thirty Two Pesos"; break;
					case 33: cout << "Thirty Three Pesos"; break;
					case 34: cout << "Thirty Four Pesos"; break;
					case 35: cout << "Thirty Five Pesos"; break;
					case 36: cout << "Thirty Six Pesos"; break;
					case 37: cout << "Thirty Seven Pesos"; break;
					case 38: cout << "Thirty Eight Pesos"; break;
					case 39: cout << "Thirty Nine Pesos"; break;
					case 40: cout << "Fourty Pesos"; break;
					case 41: cout << "Fourty One Pesos"; break;
					case 42: cout << "Fourty Two ThreePesos"; break;
					case 43: cout << "Fourty Three Pesos"; break;
					case 44: cout << "Fourty Four Pesos"; break;
					case 45: cout << "Fourty Five Pesos"; break;
					case 46: cout << "Fourty Six Pesos"; break;
					case 47: cout << "Fourty Seven Pesos"; break;
					case 48: cout << "Fourty Eight Pesos";break;
					case 49: cout << "Fourty Nine Pesos"; break;
					case 50: cout << "Fifty Pesos"; break;
					case 51: cout << "Fifty One Pesos"; break;
					case 52: cout << "Fifty Two Pesos"; break;
					case 53: cout << "Fifty Three Pesos";break;
					case 54: cout << "Fifty Four Pesos"; break;
					case 55: cout << "Fifty Five Pesos"; break;
					case 56: cout << "Fifty Six Pesos"; break;
					case 57: cout << "Fifty Seven Pesos"; break;
					case 58: cout << "Fifty Eight Pesos"; break;
					case 59: cout << "Fifty Nine Pesos"; break;
					case 60: cout << "Sixty Pesos"; break;
					case 61: cout << "Sixty One Pesos"; break;
					case 62: cout << "Sixty Four Pesos"; break;
					case 63: cout << "Sixty Three Pesos";break;
					case 64: cout << "Sixty Four Pesos"; break;
					case 65: cout << "Sixty Five Pesos"; break;
					case 66: cout << "Sixty Six Pesos"; break;
					case 67: cout << "Sixty Seven Pesos"; break;
					case 68: cout << "Sixty Eight Pesos"; break;
					case 69: cout << "Sixty Nine Pesos"; break;
					case 70: cout << "Seventy Pesos"; break;
					case 71: cout << "Seventy One Pesos"; break;
					case 72: cout << "Seventy Four Pesos"; break;
					case 73: cout << "Seventy Three Pesos";break;
					case 74: cout << "Seventy Four Pesos"; break;
					case 75: cout << "Seventy Five Pesos"; break;
					case 76: cout << "Seventy Six Pesos"; break;
					case 77: cout << "Seventy Seven Pesos"; break;
					case 78: cout << "Seventy Eight Pesos"; break;
					case 79: cout << "Seventy Nine Pesos"; break;
					case 80: cout << "Eighty Pesos"; break;
					case 81: cout << "Eighty One Pesos"; break;
					case 82: cout << "Eighty Four Pesos"; break;
					case 83: cout << "Eighty Three Pesos";break;
					case 84: cout << "Eighty Four Pesos"; break;
          case 85: cout << "Eighty Six Pesos"; break;
					case 86: cout << "Eighty Five Pesos"; break;
					case 87: cout << "Eighty Seven Pesos"; break;
					case 88: cout << "Eighty Eight Pesos"; break;
					case 89: cout << "Eighty Nine Pesos"; break;
					case 90: cout << "Ninety Pesos"; break;
					case 91: cout << "Ninety One Pesos"; break;
					case 92: cout << "Ninety Four Pesos"; break;
					case 93: cout << "Ninety Three Pesos";break;
					case 94: cout << "Ninety Four Pesos"; break;
          case 95: cout << "Ninety Five Pesos"; break;
					case 96: cout << "Ninety Six Pesos"; break;
					case 97: cout << "Ninety Seven Pesos"; break;
					case 98: cout << "Ninety Eight Pesos"; break;
					case 99: cout << "Ninety Nine Pesos"; break;
					}
					tmpDollar=tmpAmounttoConvert / 52.0880;
				  tmpPound=tmpAmounttoConvert / 90.6227;
					tmpFranc=tmpAmounttoConvert / 39.3860;
					tmpDinar=tmpAmounttoConvert / 138.2195;
					tmpRial=tmpAmounttoConvert / 13.8883;
					tmpRupial=tmpAmounttoConvert / 0.0056;
					tmpBaht=tmpAmounttoConvert / 1.3288;
					tmpDirham=tmpAmounttoConvert / 14.1821;
					tmpEuro=tmpAmounttoConvert / 61.7243;
					cout << "\n\n\nConverted to:\n\n";
					cout << "\tCurrency				Amount\n\n";
					cout << "\tDollar\t\t\t\t\t" << tmpDollar << " Dollar\n";
					cout << "\tPound\t\t\t\t\t" << tmpPound << " Pound\n";
					cout << "\tFranc\t\t\t\t\t" << tmpFranc << " Franc\n";
					cout << "\tDinar\t\t\t\t\t" << tmpDinar << " Dinar\n";
					cout << "\tRial\t\t\t\t\t" << tmpRial << " Rial\n";
					cout << "\tRupial\t\t\t\t\t" << tmpRupial << " Rupial\n";
					cout << "\tBaht\t\t\t\t\t" << tmpBaht << " Baht\n";
					cout << "\tDirham\t\t\t\t\t" << tmpDirham << " Dirham\n";
					cout << "\tEuro\t\t\t\t\t" << tmpEuro << " Euro\n\n";
					cout<<"\n";
		return 0;
}
```

