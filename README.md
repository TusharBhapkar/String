# String
this the answer of question How to remove extra spaces between String 
String s="     askjbdf   aksb   askbh  asbff khk    ";
		s=s.trim();
		String ss="";
		
		for (int i = 0; i < s.length(); i++)
		{
			if (s.charAt(i)==' ' && s.charAt(i+1)==' ')
			{
				
			} else
			{
				ss=ss+s.charAt(i);
			}
		}
		
		System.out.println("All Extra spaces are removed:: \n"+ss);
