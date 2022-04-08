# temperature_conversion

    int a;
    float t,f,d;
    printf("*For conversion of Temperature from Degree to Farenheit enter 1\n");
    printf("*For conversion of Temperature from Farenheit to Degree enter 2\n\t");
    scanf("%d",&a);

    if(a==1||a==2)
     {
      if(a==1)
      {
       printf("Enter the temperature value in Degree: \n\t");
       scanf("%f",&d);
       printf("\nTemperarure in degree celscius: %f\n",d);
       t=(d*9/5)+32;
       printf("\nTemperature in Farenheit:");
       printf("%f",t);
      }
      else
      {
       printf("Enter the temperature value in Farenheit: \n\t");
       scanf("%f",&f);
       printf("\nTemperature in Farenheit: %f\n",f);
       t=(f-32*5)/9;
       printf("\nTemperature in Degree:");
       printf("%f",t);
      }
     }
    else
     {
      printf("\n\t\t\tError!!! Enter specific value....");
     }
