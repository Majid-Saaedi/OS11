سید مجید ساعدی ، تمرین 11

----------------------------

سوال 2
    
    \documentclass{article}

    \usepackage[utf8]{inputenc}

    \usepackage{graphicx}

    \usepackage{listings}

    \title{Majid}

    \author{Majid Saaedi}

    \date{June 2021}

    \begin{document}

    \maketitle

    \begin{center}

    \section*{Biography}

    Majid Saaedi\\

    February 27 , 2000\\

    Computer Engineer\\

    Sadjad University\\

    Mashhad , Iran\\

    \section*{Image}

    \includegraphics{cer.jpg}

    \section*{\\Table}

    \begin{table}[h!]

    \begin{center}

    \label{tab:table1}

    \begin{tabular}{l|c|r}

    \textbf{Value 1} & \textbf{Value 2} & \textbf{Value 3}\\

    \hline

    1 & 4 & 7\\

    2 & 5 & 8\\

    3 & 6 & 9\\

    \end{tabular}

    \end{center}

    \end{table}

    \section*{Math}

    \begin{align*}

      F(x) &= \int^a_b \ x^3 dx

    \end{align*}

    \section*{Code}

    \begin{lstlisting}

    int main()

    {

        int n,e,k,sum=0;

        cout<<"Enter a number";

        cin>>n;

        while(n)

        {

            k=n/10;

            e=n%10;

            sum+=e;

            n=k;

        }

        cout<<sum;

    }

    \end{lstlisting}

    \end{center}

    \end{document}
