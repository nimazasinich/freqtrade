##########################################################################################
                                                                                          
                                       PayStore®                                          
                                        v2.3.2                                                
                                                                                          
                                   Phoebus Tecnologia                                     
                                                                                          
##########################################################################################

# Architecture

	+---------------------------------------------+ +-------------------------------+   |                 
	|                 Adquirentes                 | |             Apps              |   |                 
	|                                             | |                               |   |                 
	|                                             | |                               |   |                 
	|                                             | |                               |   |                 
	|   +----------+ +-----------+ +----------+   | |   +----------+ +-----------+  |   |                 
	|   |   Adiq   | | Conductor | |  Global  |   | |   |   Calc   | | Relatórios|  |   |                 
	|   |          | |           | |          |   | |   |          | |           |  |   | Camada          
	|   +----------+ +-----------+ +----------+   | |   +----------+ +-----------+  |   | Script          
	|   +----------+ +----------+ +-----------+   | |   +----------+ +-----------+  |   |                 
	|   |   Cielo  | |   Stone  | | PagSeguro |   | |   |   Skin   | |  Taxa ao  |  |   |                 
	|   |          | |          | |           |   | |   |          | |  Portador |  |   |                 
	|   +----------+ +----------+ +-----------+   | |   +----------+ +-----------+  |   |                 
	+---------------------------------------------+ +-------------------------------+   |                 
	+-------------------+ +----------+ +----------+ +-------------------------------+   |                 
	|         Tef       | |   TefUI  | |TefVoucher| |             PayStore          |   |                 
	|                   | |          | |          | |                               |   |                 
	+-------------------+ +----------+ +----------+ +-------------------------------+   |                 
	+---------------------------------------------+ +----------+                        |                 
	|                  PhAST                      | |PhDM      |                        |                 
	|                                             | |          |                        |                 
	+---------------------------------------------+ +----------+                        |                 
																						|                 
																										  
	+-------------------------------------------------------------------------------+   |                 
	|                                                                               |   |                 
	|                                     PhVM                                      |   |                 
	|                                                                               |   | Camada          
	|                                                                               |   | Nativa          
	+-------------------------------------------------------------------------------+   |                 
	+-------------------------------------------------------------------------------+   |                 
	|                              Sistema Operacional                              |   |                 
	|                                                                               |   |                 
	+-------------------------------------------------------------------------------+   |                 

# Version History

	TefSuite(1.4.16) 	Adiq(1.0.7) 	Conductor(1.0.0) 	Fidelidade(1.0.0) 	Global(1.3.6) 	PayStore(1.0.25) 	PhAST(9.4.30) 	PhDM(1.8.4) 	PhVM(1.4.27) 	Stone(1.0.9) 	Tef(1.4.33) 	TefUI(1.4.15) 	TefVoucher(1.0.10) 	TefSuite(1.4.16)
	TefSuite(1.4.17) 	Adiq(1.0.7) 	Conductor(1.0.0) 	Fidelidade(1.0.0) 	Global(1.3.6) 	PayStore(1.0.26) 	PhAST(9.4.31) 	PhDM(1.8.4) 	PhVM(1.4.28) 	Stone(1.0.9) 	Tef(1.4.34) 	TefUI(1.4.15) 	TefVoucher(1.0.10) 	TefSuite(1.4.17)
	TefSuite(1.4.18) 	Adiq(1.0.7) 	Conductor(1.0.0) 	Fidelidade(1.0.0) 	Global(1.3.6) 	PayStore(1.0.27) 	PhAST(9.4.32) 	PhDM(1.8.4) 	PhVM(1.4.28) 	Stone(1.0.9) 	Tef(1.4.35) 	TefUI(1.4.16) 	TefVoucher(1.0.10) 	TefSuite(1.4.18)
	TefSuite(1.4.21) 	Adiq(1.0.8) 	Conductor(1.0.1) 	Fidelidade(1.0.1) 	Global(1.3.7) 	PayStore(1.0.31) 	PhAST(9.4.36) 	PhDM(1.8.4) 	PhVM(1.4.31) 	Stone(1.0.10) 	Tef(1.4.36) 	TefUI(1.4.21) 	TefVoucher(1.0.16) 	TefSuite(1.4.21)
	TefSuite(1.4.22) 	Adiq(1.0.9) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.32) 	PhAST(9.4.37) 	PhDM(1.8.4) 	PhVM(1.4.32) 	Stone(1.0.11) 	Tef(1.4.37) 	TefUI(1.4.22) 	TefVoucher(1.0.16) 	TefSuite(1.4.22)
	TefSuite(1.4.23) 	Adiq(1.0.9) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.33) 	PhAST(9.4.38) 	PhDM(1.8.4) 	PhVM(1.4.33) 	Stone(1.0.11) 	Tef(1.4.38) 	TefUI(1.4.23) 	TefVoucher(1.0.16) 	TefSuite(1.4.23)
	TefSuite(1.4.24) 	Adiq(1.0.9) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.34) 	PhAST(9.4.39) 	PhDM(1.8.4) 	PhVM(1.4.33) 	Stone(1.0.11) 	Tef(1.4.39) 	TefUI(1.4.24) 	TefVoucher(1.0.16) 	TefSuite(1.4.24)
	TefSuite(1.4.25) 	Adiq(1.0.9) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.35) 	PhAST(9.4.40) 	PhDM(1.8.4) 	PhVM(1.4.35) 	Stone(1.0.11) 	Tef(1.4.40) 	TefUI(1.4.24) 	TefVoucher(1.0.16) 	TefSuite(1.4.25)
	TefSuite(1.4.26) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.36) 	PhAST(9.4.41) 	PhDM(1.8.4) 	PhVM(1.4.36) 	Stone(1.0.12) 	Tef(1.4.41) 	TefUI(1.4.25) 	TefVoucher(1.0.17) 	TefSuite(1.4.26)
	TefSuite(1.4.27) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.37) 	PhAST(9.4.42) 	PhDM(1.8.4) 	PhVM(1.4.37) 	Stone(1.0.12) 	Tef(1.4.42) 	TefUI(1.4.25) 	TefVoucher(1.0.18) 	TefSuite(1.4.27)
	TefSuite(1.4.28) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.37) 	PhAST(9.4.43) 	PhDM(1.8.4) 	PhVM(1.4.37) 	Stone(1.0.12) 	Tef(1.4.42) 	TefUI(1.4.25) 	TefVoucher(1.0.18) 	TefSuite(1.4.28)
	TefSuite(1.4.29) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.37) 	PhAST(9.4.44) 	PhDM(1.8.4) 	PhVM(1.4.38) 	Stone(1.0.12) 	Tef(1.4.42) 	TefUI(1.4.25) 	TefVoucher(1.0.19) 	TefSuite(1.4.29)
	TefSuite(1.4.30) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.37) 	PhAST(9.4.45) 	PhDM(1.8.4) 	PhVM(1.4.38) 	Stone(1.0.12) 	Tef(1.4.43) 	TefUI(1.4.25) 	TefVoucher(1.0.19) 	TefSuite(1.4.30)
	TefSuite(1.4.31) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.38) 	PhAST(9.4.46) 	PhDM(1.8.4) 	PhVM(1.4.38) 	Stone(1.0.12) 	Tef(1.4.44) 	TefUI(1.4.26) 	TefVoucher(1.0.19) 	TefSuite(1.4.31)
	TefSuite(1.4.32) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.38) 	PhAST(9.4.47) 	PhDM(1.8.4) 	PhVM(1.4.39) 	Stone(1.0.12) 	Tef(1.4.44) 	TefUI(1.4.26) 	TefVoucher(1.0.19) 	TefSuite(1.4.32)
	TefSuite(1.4.33) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.38) 	PhAST(9.4.47) 	PhDM(1.8.4) 	PhVM(1.4.40) 	Stone(1.0.12) 	Tef(1.4.44) 	TefUI(1.4.26) 	TefVoucher(1.0.19) 	TefSuite(1.4.33)
	TefSuite(1.4.34) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.39) 	PhAST(9.4.48) 	PhDM(1.8.4) 	PhVM(1.4.41) 	Stone(1.0.12) 	Tef(1.4.45) 	TefUI(1.4.27) 	TefVoucher(1.0.19) 	TefSuite(1.4.34)
	TefSuite(1.4.35) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.40) 	PhAST(9.4.49) 	PhDM(1.8.4) 	PhVM(1.4.42) 	Stone(1.0.12) 	Tef(1.4.46) 	TefUI(1.4.27) 	TefVoucher(1.0.20) 	TefSuite(1.4.35)
	TefSuite(1.4.36) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.41) 	PhAST(9.4.50) 	PhDM(1.8.4) 	PhVM(1.4.43) 	Stone(1.0.13) 	Tef(1.4.47) 	TefUI(1.4.28) 	TefVoucher(1.0.21) 	TefSuite(1.4.36)
	TefSuite(1.4.37) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.41) 	PhAST(9.4.51) 	PhDM(1.8.4) 	PhVM(1.4.43) 	Stone(1.0.13) 	Tef(1.4.47) 	TefUI(1.4.29) 	TefVoucher(1.0.21) 	TefSuite(1.4.37)
	TefSuite(1.4.38) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.41) 	PhAST(9.4.51) 	PhDM(1.8.4) 	PhVM(1.4.44) 	Stone(1.0.13) 	Tef(1.4.47) 	TefUI(1.4.29) 	TefVoucher(1.0.21) 	TefSuite(1.4.38)
	TefSuite(1.4.39) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.42) 	PhAST(9.4.52) 	PhDM(1.8.4) 	PhVM(1.4.44) 	Stone(1.0.13) 	Tef(1.4.48) 	TefUI(1.4.30) 	TefVoucher(1.0.21) 	TefSuite(1.4.39)
	TefSuite(1.4.40) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.42) 	PhAST(9.4.52) 	PhDM(1.8.4) 	PhVM(1.4.44) 	Stone(1.0.13) 	Tef(1.4.48) 	TefUI(1.4.30) 	TefVoucher(1.0.21) 	TefSuite(1.4.40)
	TefSuite(1.4.41) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.42) 	PhAST(9.4.52) 	PhDM(1.8.4) 	PhVM(1.4.44) 	Stone(1.0.13) 	Tef(1.4.48) 	TefUI(1.4.31) 	TefVoucher(1.0.21) 	TefSuite(1.4.41)
	TefSuite(1.4.42) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.42) 	PhAST(9.4.52) 	PhDM(1.8.4) 	PhVM(1.4.44) 	Stone(1.0.13) 	Tef(1.4.48) 	TefUI(1.4.32) 	TefVoucher(1.0.21) 	TefSuite(1.4.42)
	TefSuite(1.4.43) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.42) 	PhAST(9.4.53) 	PhDM(1.8.4) 	PhVM(1.4.44) 	Stone(1.0.13) 	Tef(1.4.48) 	TefUI(1.4.33) 	TefVoucher(1.0.21) 	TefSuite(1.4.43)
	TefSuite(1.4.44) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.43) 	PhAST(9.4.54) 	PhDM(1.8.4.1) 	PhVM(1.4.45) 	Stone(1.0.13) 	Tef(1.4.49) 	TefUI(1.4.34) 	TefVoucher(1.0.22) 	TefSuite(1.4.44)
	TefSuite(1.4.45) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.43) 	PhAST(9.4.54) 	PhDM(1.8.4.1) 	PhVM(1.4.45) 	Stone(1.0.13) 	Tef(1.4.49) 	TefUI(1.4.35) 	TefVoucher(1.0.22) 	TefSuite(1.4.45)
	TefSuite(1.4.46) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.44) 	PhAST(9.4.55) 	PhDM(1.8.4.1) 	PhVM(1.4.45) 	Stone(1.0.13) 	Tef(1.4.50) 	TefUI(1.4.35) 	TefVoucher(1.0.22) 	TefSuite(1.4.46)
	TefSuite(1.4.47) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.45) 	PhAST(9.4.55) 	PhDM(1.8.4.1) 	PhVM(1.4.45) 	Stone(1.0.13) 	Tef(1.4.50) 	TefUI(1.4.35) 	TefVoucher(1.0.22) 	TefSuite(1.4.47)
	TefSuite(1.4.48) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.46) 	PhAST(9.4.56) 	PhDM(1.8.4.1) 	PhVM(1.4.45) 	Stone(1.0.13) 	Tef(1.4.50) 	TefUI(1.4.35) 	TefVoucher(1.0.22) 	TefSuite(1.4.48)
	TefSuite(1.4.49) 	Adiq(1.0.10) 	Conductor(1.0.2) 	Fidelidade(1.0.2) 	Global(1.3.8) 	PayStore(1.0.46) 	PhAST(9.4.56) 	PhDM(1.8.4.1) 	PhVM(1.4.45) 	Stone(1.0.13) 	Tef(1.4.50) 	TefUI(1.4.35) 	TefVoucher(1.0.22) 	TefSuite(1.4.49)
	TefSuite(1.5.1) 	Adiq(1.1.0) 	Conductor(1.1.0) 	Fidelidade(1.0.2) 	Global(1.4.0) 	PayStore(1.1.0) 	PhAST(9.5.0) 	PhDM(1.8.4) 	PhVM(1.5.0) 	Stone(1.1.0) 	Tef(1.5.0) 	TefUI(1.5.0) 	TefVoucher(1.1.0) 	TefSuite(1.5.1) 	Cielo(1.0.0)
	TefSuite(1.5.2) 	Adiq(1.1.0) 	Conductor(1.1.0) 	Fidelidade(1.0.2) 	Global(1.4.0) 	PayStore(1.1.1) 	PhAST(9.5.1) 	PhDM(1.8.4) 	PhVM(1.5.1) 	Stone(1.1.1) 	Tef(1.5.1) 	TefUI(1.5.1) 	TefVoucher(1.1.1) 	TefSuite(1.5.2) 	Cielo(1.0.1)
	TefSuite(1.5.3) 	Adiq(1.1.1) 	Conductor(1.1.1) 	Fidelidade(1.0.2) 	Global(1.4.1) 	PayStore(1.1.2) 	PhAST(9.5.2) 	PhDM(1.8.5) 	PhVM(1.5.2) 	Stone(1.1.2) 	Tef(1.5.2) 	TefUI(1.5.2) 	TefVoucher(1.1.2) 	TefSuite(1.5.3) 	Cielo(1.0.2) 	PagSeguro(1.0.0)
	TefSuite(1.5.4) 	Adiq(1.1.2) 	Conductor(1.1.1) 	Fidelidade(1.0.2) 	Global(1.4.1) 	PayStore(1.1.3) 	PhAST(9.5.3) 	PhDM(1.8.5) 	PhVM(1.5.4) 	Stone(1.1.3) 	Tef(1.5.3) 	TefUI(1.5.3) 	TefVoucher(1.1.3) 	TefSuite(1.5.4) 	Cielo(1.0.3) 	PagSeguro(1.0.1)
	TefSuite(1.5.5) 	Adiq(1.1.3) 	Conductor(1.1.2) 	Fidelidade(1.0.2) 	Global(1.4.3) 	PayStore(1.1.4) 	PhAST(9.5.4) 	PhDM(1.8.5) 	PhVM(1.5.5) 	Stone(1.1.4) 	Tef(1.5.4) 	TefUI(1.5.4) 	TefVoucher(1.1.4) 	TefSuite(1.5.5) 	Cielo(1.0.4) 	PagSeguro(1.0.2)
	TefSuite(1.5.6) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.5) 	PhDM(1.8.5) 	PhVM(1.5.6) 	Stone(1.1.5) 	Tef(1.5.5) 	TefUI(1.5.5) 	TefVoucher(1.1.5) 	TefSuite(1.5.6) 	Cielo(1.0.5) 	PagSeguro(1.0.3) 	Banese(1.0.0)
	TefSuite(1.5.7) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.6) 	PhDM(1.8.5) 	PhVM(1.5.7) 	Stone(1.1.5) 	Tef(1.5.6) 	TefUI(1.5.6) 	TefVoucher(1.1.6) 	TefSuite(1.5.7) 	Cielo(1.0.5) 	PagSeguro(1.0.3) 	Banese(1.0.0)
	TefSuite(1.5.8) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.7) 	PhDM(1.8.6) 	PhVM(1.5.8) 	Stone(1.1.5) 	Tef(1.5.7) 	TefUI(1.5.7) 	TefVoucher(1.1.6) 	TefSuite(1.5.8) 	Cielo(1.0.5) 	PagSeguro(1.0.3) 	Banese(1.0.0)
	TefSuite(1.5.9) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.8) 	PhDM(1.8.6) 	PhVM(1.5.8) 	Stone(1.1.5) 	Tef(1.5.7) 	TefUI(1.5.7) 	TefVoucher(1.1.6) 	TefSuite(1.5.9) 	Cielo(1.0.5) 	PagSeguro(1.0.4) 	Banese(1.0.0)
	TefSuite(1.5.10) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.9) 	PhDM(1.8.6) 	PhVM(1.5.8) 	Stone(1.1.5) 	Tef(1.5.8) 	TefUI(1.5.7) 	TefVoucher(1.1.6) 	TefSuite(1.5.10) 	Cielo(1.0.5) 	PagSeguro(1.0.5) 	Banese(1.0.0)
	TefSuite(1.5.11) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.10) 	PhDM(1.8.6) 	PhVM(1.5.8) 	Stone(1.1.5) 	Tef(1.5.9) 	TefUI(1.5.7) 	TefVoucher(1.1.6) 	TefSuite(1.5.11) 	Cielo(1.0.5) 	PagSeguro(1.0.5) 	Banese(1.0.0)
	TefSuite(1.5.12) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.11) 	PhDM(1.8.6) 	PhVM(1.5.9) 	Stone(1.1.5) 	Tef(1.5.10) 	TefUI(1.5.7) 	TefVoucher(1.1.6) 	TefSuite(1.5.12) 	Cielo(1.0.5) 	PagSeguro(1.0.5) 	Banese(1.0.0)
	TefSuite(1.5.13) 	Adiq(1.1.4) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.12) 	PhDM(1.8.6) 	PhVM(1.5.9) 	Stone(1.1.5) 	Tef(1.5.10) 	TefUI(1.5.8) 	TefVoucher(1.1.6) 	TefSuite(1.5.13) 	Cielo(1.0.5) 	PagSeguro(1.0.5) 	Banese(1.0.0)
	TefSuite(1.5.14) 	Adiq(1.1.5) 	Conductor(1.1.3) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.5) 	PhAST(9.5.13) 	PhDM(1.8.6) 	PhVM(1.5.9) 	Stone(1.1.5) 	Tef(1.5.11) 	TefUI(1.5.9) 	TefVoucher(1.1.6) 	TefSuite(1.5.14) 	Cielo(1.0.5) 	PagSeguro(1.0.5) 	Banese(1.0.0) 	Senff(1.0.0)
	TefSuite(1.5.15) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.6) 	PhAST(9.5.14) 	PhDM(1.8.6) 	PhVM(1.5.10) 	Stone(1.1.5) 	Tef(1.5.12) 	TefUI(1.5.9) 	TefVoucher(1.1.7) 	TefSuite(1.5.15) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.1) 	Senff(1.0.0)
	TefSuite(1.5.16) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.7) 	PhAST(9.5.14) 	PhDM(1.8.6) 	PhVM(1.5.10) 	Stone(1.1.5) 	Tef(1.5.12) 	TefUI(1.5.9) 	TefVoucher(1.1.7) 	TefSuite(1.5.16) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.1) 	Senff(1.0.0)
	TefSuite(1.5.17) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.7) 	PhAST(9.5.14) 	PhDM(1.8.6) 	PhVM(1.5.10) 	Stone(1.1.5) 	Tef(1.5.13) 	TefUI(1.5.9) 	TefVoucher(1.1.7) 	TefSuite(1.5.17) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.1) 	Senff(1.0.0)
	TefSuite(1.5.18) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.4) 	PayStore(1.1.7) 	PhAST(9.5.15) 	PhDM(1.8.6) 	PhVM(1.5.11) 	Stone(1.1.5) 	Tef(1.5.14) 	TefUI(1.5.9) 	TefVoucher(1.1.8) 	TefSuite(1.5.18) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.2) 	Senff(1.0.0)
	TefSuite(1.5.19) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.5) 	PayStore(1.1.7) 	PhAST(9.5.16) 	PhDM(1.8.6) 	PhVM(1.5.11) 	Stone(1.1.5) 	Tef(1.5.15) 	TefUI(1.5.9) 	TefVoucher(1.1.9) 	TefSuite(1.5.19) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.3) 	Senff(1.0.1)
	TefSuite(1.5.20) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.5) 	PayStore(1.1.7) 	PhAST(9.5.16) 	PhDM(1.8.6) 	PhVM(1.5.11) 	Stone(1.1.5) 	Tef(1.5.15) 	TefUI(1.5.9) 	TefVoucher(1.1.9) 	TefSuite(1.5.20) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.3) 	Senff(1.0.1)
	TefSuite(1.5.21) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.5) 	PayStore(1.1.7) 	PhAST(9.5.17) 	PhDM(1.8.6) 	PhVM(1.5.12) 	Stone(1.1.5) 	Tef(1.5.16) 	TefUI(1.5.9) 	TefVoucher(1.1.9) 	TefSuite(1.5.21) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.3) 	Senff(1.0.1)
	TefSuite(1.5.22) 	Adiq(1.1.5) 	Conductor(1.1.4) 	Fidelidade(1.0.2) 	Global(1.4.5) 	PayStore(1.1.7) 	PhAST(9.5.17) 	PhDM(1.8.6) 	PhVM(1.5.13) 	Stone(1.1.5) 	Tef(1.5.16) 	TefUI(1.5.9) 	TefVoucher(1.1.9) 	TefSuite(1.5.22) 	Cielo(1.0.6) 	PagSeguro(1.0.5) 	Banese(1.0.3) 	Senff(1.0.1)
	TefSuite(1.5.23) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.8) 	PhAST(9.5.18) 	PhDM(1.9.0) 	PhVM(1.5.14) 	Stone(1.1.5) 	Tef(1.5.17) 	TefUI(1.5.10) 	TefVoucher(1.1.10) 	TefSuite(1.5.23) 	Cielo(1.0.7) 	PagSeguro(1.0.6) 	Banese(1.0.4) 	Senff(1.0.2)
	TefSuite(1.5.24) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.9) 	PhAST(9.5.19) 	PhDM(1.9.1) 	PhVM(1.5.15) 	Stone(1.1.5) 	Tef(1.5.18) 	TefUI(1.5.11) 	TefVoucher(1.1.10) 	TefSuite(1.5.24) 	Cielo(1.0.7) 	PagSeguro(1.0.6) 	Banese(1.0.5) 	Senff(1.0.3)
	TefSuite(1.5.25) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.9) 	PhAST(9.5.20) 	PhDM(1.9.1) 	PhVM(1.5.16) 	Stone(1.1.5) 	Tef(1.5.19) 	TefUI(1.5.12) 	TefVoucher(1.1.10) 	TefSuite(1.5.25) 	Cielo(1.0.7) 	PagSeguro(1.0.6) 	Banese(1.0.5) 	Senff(1.0.3)
	TefSuite(1.5.26) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.10) 	PhAST(9.5.21) 	PhDM(1.9.1) 	PhVM(1.5.17) 	Stone(1.1.5) 	Tef(1.5.20) 	TefUI(1.5.13) 	TefVoucher(1.1.10) 	TefSuite(1.5.26) 	Cielo(1.0.7) 	PagSeguro(1.0.7) 	Banese(1.0.5) 	Senff(1.0.3)
	TefSuite(1.5.27) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.10) 	PhAST(9.5.21) 	PhDM(1.9.1) 	PhVM(1.5.17) 	Stone(1.1.5) 	Tef(1.5.21) 	TefUI(1.5.13) 	TefVoucher(1.1.10) 	TefSuite(1.5.27) 	Cielo(1.0.7) 	PagSeguro(1.0.7) 	Banese(1.0.5) 	Senff(1.0.3)
	TefSuite(1.5.28) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.11) 	PhAST(9.5.22) 	PhDM(1.9.1) 	PhVM(1.5.18) 	Stone(1.1.5) 	Tef(1.5.22) 	TefUI(1.5.13) 	TefVoucher(1.1.11) 	TefSuite(1.5.28) 	Cielo(1.0.7) 	PagSeguro(1.0.7) 	Banese(1.0.6) 	Senff(1.0.3)
	TefSuite(1.5.29) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.6) 	PayStore(1.1.11) 	PhAST(9.5.23) 	PhDM(1.9.1) 	PhVM(1.5.19) 	Stone(1.1.5) 	Tef(1.5.23) 	TefUI(1.5.14) 	TefVoucher(1.1.11) 	TefSuite(1.5.29) 	Cielo(1.0.7) 	PagSeguro(1.0.7) 	Banese(1.0.6) 	Senff(1.0.3)
	TefSuite(1.5.30) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.7) 	PayStore(1.1.11) 	PhAST(9.5.23) 	PhDM(1.9.1) 	PhVM(1.5.20) 	Stone(1.1.5) 	Tef(1.5.23) 	TefUI(1.5.14) 	TefVoucher(1.1.11) 	TefSuite(1.5.30) 	Cielo(1.0.8) 	PagSeguro(1.0.7) 	Banese(1.0.6) 	Senff(1.0.3)
	TefSuite(1.5.31) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.7) 	PayStore(1.1.12) 	PhAST(9.5.23) 	PhDM(1.9.1) 	PhVM(1.5.21) 	Stone(1.1.5) 	Tef(1.5.25) 	TefUI(1.5.15) 	TefVoucher(1.1.12) 	TefSuite(1.5.31) 	Cielo(1.0.9) 	PagSeguro(1.0.7) 	Banese(1.0.6) 	Senff(1.0.4) 	Acqio(1.0.0)
	TefSuite(1.5.32) 	Adiq(1.1.6) 	Conductor(1.1.5) 	Fidelidade(1.0.3) 	Global(1.4.7) 	PayStore(1.1.13) 	PhAST(9.5.24) 	PhDM(1.9.1) 	PhVM(1.5.22) 	Stone(1.1.5) 	Tef(1.5.26) 	TefUI(1.5.15) 	TefVoucher(1.1.12) 	TefSuite(1.5.32) 	Cielo(1.0.9) 	PagSeguro(1.0.7) 	Banese(1.0.6) 	Senff(1.0.4) 	Acqio(1.0.0)
	TefSuite(1.5.33) 	Adiq(1.1.8) 	Conductor(1.1.7) 	Fidelidade(1.0.4) 	Global(1.4.9) 	PayStore(1.1.14) 	PhAST(9.5.25) 	PhDM(1.9.1) 	PhVM(1.5.22) 	Stone(1.1.7) 	Tef(1.5.27) 	TefUI(1.5.16) 	TefVoucher(1.1.12) 	TefSuite(1.5.33) 	Cielo(1.0.11) 	PagSeguro(1.0.9) 	Banese(1.0.8) 	Senff(1.0.6) 	Acqio(1.0.2)
	TefSuite(1.5.34) 	Adiq(1.1.9) 	Conductor(1.1.8) 	Fidelidade(1.0.4) 	Global(1.4.10) 	PayStore(1.1.15) 	PhAST(9.5.25) 	PhDM(1.9.1) 	PhVM(1.5.23) 	Stone(1.1.8) 	Tef(1.5.28) 	TefUI(1.5.16) 	TefVoucher(1.1.12) 	TefSuite(1.5.34) 	Cielo(1.0.12) 	PagSeguro(1.0.10) 	Banese(1.0.9) 	Senff(1.0.7) 	Acqio(1.0.3)
	TefSuite(1.5.34.4) 	Adiq(1.1.9) 	Conductor(1.1.8) 	Fidelidade(1.0.4) 	Global(1.4.10) 	PayStore(1.1.15) 	PhAST(9.5.25) 	PhDM(1.9.1) 	PhVM(1.5.23) 	Stone(1.1.8) 	Tef(1.5.28.1) 	TefUI(1.5.16) 	TefVoucher(1.1.12) 	TefSuite(1.5.34.4) 	Cielo(1.0.12) 	PagSeguro(1.0.10) 	Banese(1.0.9) 	Senff(1.0.7) 	Acqio(1.0.3)
	TefSuite(1.5.35) 	Adiq(1.1.9) 	Conductor(1.1.8) 	Fidelidade(1.0.4) 	Global(1.4.10) 	PayStore(1.1.16) 	PhAST(9.5.26) 	PhDM(1.9.1) 	PhVM(1.5.23) 	Stone(1.1.8) 	Tef(1.5.28) 	TefUI(1.5.16) 	TefVoucher(1.1.12) 	TefSuite(1.5.35) 	Cielo(1.0.12) 	PagSeguro(1.0.10) 	Banese(1.0.9) 	Senff(1.0.7) 	Acqio(1.0.3)
	TefSuite(1.5.36) 	Adiq(1.1.10) 	Conductor(1.1.8) 	Fidelidade(1.0.4) 	Global(1.4.10) 	PayStore(1.1.17) 	PhAST(9.5.27) 	PhDM(1.9.1) 	PhVM(1.5.24) 	Stone(1.1.8) 	Tef(1.5.29) 	TefUI(1.5.17) 	TefVoucher(1.1.13) 	TefSuite(1.5.36) 	Cielo(1.0.12) 	PagSeguro(1.0.10) 	Banese(1.0.9) 	Senff(1.0.7) 	Acqio(1.0.3)
	TefSuite(1.5.37) 	Adiq(1.1.10) 	Conductor(1.1.8) 	Fidelidade(1.0.4) 	Global(1.4.10) 	PayStore(1.1.18) 	PhAST(9.5.28) 	PhDM(1.9.1) 	PhVM(1.5.25) 	Stone(1.1.8) 	Tef(1.5.30) 	TefUI(1.5.18) 	TefVoucher(1.1.13) 	TefSuite(1.5.37) 	Cielo(1.0.13) 	PagSeguro(1.0.10) 	Banese(1.0.9) 	Senff(1.0.7) 	Acqio(1.0.3)
	TefSuite(1.5.38) 	Adiq(1.1.10) 	Conductor(1.1.8) 	Fidelidade(1.0.4) 	Global(1.4.10) 	PayStore(1.1.19) 	PhAST(9.5.29) 	PhDM(1.9.2) 	PhVM(1.5.26) 	Stone(1.1.8) 	Tef(1.5.31) 	TefUI(1.5.19) 	TefVoucher(1.1.13) 	TefSuite(1.5.38) 	Cielo(1.0.14) 	PagSeguro(1.0.10) 	Banese(1.0.9) 	Senff(1.0.7) 	Acqio(1.0.3)
	TefSuite(1.5.39) 	Adiq(1.1.11) 	Conductor(1.1.9) 	Fidelidade(1.0.5) 	Global(1.4.11) 	PayStore(1.1.20) 	PhAST(9.5.30) 	PhDM(1.9.3) 	PhVM(1.5.27) 	Stone(1.1.9) 	Tef(1.5.32) 	TefUI(1.5.20) 	TefVoucher(1.1.14) 	TefSuite(1.5.39) 	Cielo(1.0.15) 	PagSeguro(1.0.11) 	Banese(1.0.10) 	Senff(1.0.8) 	Acqio(1.0.4)
	TefSuite(1.5.40) 	Adiq(1.1.11) 	Conductor(1.1.10) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.20) 	PhAST(9.5.31) 	PhDM(1.9.3) 	PhVM(1.5.28) 	Stone(1.1.10) 	Tef(1.5.33) 	TefUI(1.5.21) 	TefVoucher(1.1.14) 	TefSuite(1.5.40) 	Cielo(1.0.16) 	PagSeguro(1.0.12) 	Banese(1.0.11) 	Senff(1.0.9) 	Acqio(1.0.4)
	TefSuite(1.5.41) 	Adiq(1.1.11) 	Conductor(1.1.10) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.20) 	PhAST(9.5.32) 	PhDM(1.9.3) 	PhVM(1.5.28) 	Stone(1.1.10) 	Tef(1.5.34) 	TefUI(1.5.22) 	TefVoucher(1.1.14) 	TefSuite(1.5.41) 	Cielo(1.0.16) 	PagSeguro(1.0.12) 	Banese(1.0.11) 	Senff(1.0.9) 	Acqio(1.0.4) 	TKS(1.0.0)
	TefSuite(1.5.42) 	Adiq(1.1.11) 	Conductor(1.1.10) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.20) 	PhAST(9.5.33) 	PhDM(1.9.3) 	PhVM(1.5.29) 	Stone(1.1.10) 	Tef(1.5.35) 	TefUI(1.5.22) 	TefVoucher(1.1.14) 	TefSuite(1.5.42) 	Cielo(1.0.16) 	PagSeguro(1.0.12) 	Banese(1.0.11) 	Senff(1.0.9) 	Acqio(1.0.4) 	TKS(1.0.0)
	TefSuite(1.5.43) 	Adiq(1.1.11) 	Conductor(1.1.11) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.20) 	PhAST(9.5.34) 	PhDM(1.9.3) 	PhVM(1.5.29) 	Stone(1.1.10) 	Tef(1.5.36) 	TefUI(1.5.23) 	TefVoucher(1.1.14) 	TefSuite(1.5.43) 	Cielo(1.0.16) 	PagSeguro(1.0.12) 	Banese(1.0.11) 	Senff(1.0.10) 	Acqio(1.0.4) 	TKS(1.0.1)
	TefSuite(1.5.44) 	Adiq(1.1.11) 	Conductor(1.1.11) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.21) 	PhAST(9.5.34) 	PhDM(1.9.3) 	PhVM(1.5.30) 	Stone(1.1.10) 	Tef(1.5.37) 	TefUI(1.5.23) 	TefVoucher(1.1.14) 	TefSuite(1.5.44) 	Cielo(1.0.17) 	PagSeguro(1.0.12) 	Banese(1.0.11) 	Senff(1.0.10) 	Acqio(1.0.4) 	TKS(1.0.1)
	TefSuite(1.5.45) 	Adiq(1.1.11) 	Conductor(1.1.11) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.21) 	PhAST(9.5.34) 	PhDM(1.9.3) 	PhVM(1.5.30) 	Stone(1.1.10) 	Tef(1.5.38) 	TefUI(1.5.23) 	TefVoucher(1.1.14) 	TefSuite(1.5.45) 	Cielo(1.0.17) 	PagSeguro(1.0.12) 	Banese(1.0.12) 	Senff(1.0.10) 	Acqio(1.0.4) 	TKS(1.0.2)
	TefSuite(1.5.46) 	Adiq(1.1.11) 	Conductor(1.1.11) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.21) 	PhAST(9.5.34) 	PhDM(1.9.3) 	PhVM(1.5.30) 	Stone(1.1.10) 	Tef(1.5.38) 	TefUI(1.5.24) 	TefVoucher(1.1.15) 	TefSuite(1.5.46) 	Cielo(1.0.17) 	PagSeguro(1.0.12) 	Banese(1.0.12) 	Senff(1.0.10) 	Acqio(1.0.4) 	TKS(1.0.2)
	TefSuite(1.5.47) 	Adiq(1.1.11) 	Conductor(1.1.11) 	Fidelidade(1.0.5) 	Global(1.4.12) 	PayStore(1.1.21) 	PhAST(9.5.35) 	PhDM(1.9.3) 	PhVM(1.5.31) 	Stone(1.1.10) 	Tef(1.5.38) 	TefUI(1.5.25) 	TefVoucher(1.1.15) 	TefSuite(1.5.47) 	Cielo(1.0.17) 	PagSeguro(1.0.12) 	Banese(1.0.12) 	Senff(1.0.10) 	Acqio(1.0.4) 	TKS(1.0.2)
	TefSuite(2.0.0) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.0) 	PhAST(9.6.0) 	PhDM(1.10.0) 	PhVM(1.6.0) 	Stone(1.2.0) 	Tef(1.6.0) 	TefUI(1.6.0) 	TefVoucher(1.2.0) 	TefSuite(2.0.0) 	Cielo(1.1.0) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.0)
	TefSuite(2.0.1) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.1) 	PhAST(9.6.1) 	PhDM(1.10.1) 	PhVM(1.6.1) 	Stone(1.2.0) 	Tef(1.6.1) 	TefUI(1.6.1) 	TefVoucher(1.2.1) 	TefSuite(2.0.1) 	Cielo(1.1.1) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.1)
	TefSuite(2.0.2) 	Adiq(1.2.1) 	Conductor(1.2.1) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.2) 	PhAST(9.6.2) 	PhDM(1.10.2) 	PhVM(1.6.2) 	Stone(1.2.1) 	Tef(1.6.2) 	TefUI(1.6.2) 	TefVoucher(1.2.2) 	TefSuite(2.0.2) 	Cielo(1.1.2) 	PagSeguro(1.1.1) 	Banese(1.1.1) 	Senff(1.1.1) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	TKS(1.0.0)
	TefSuite(2.0.3) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.6.3) 	PhDM(1.10.2) 	PhVM(1.6.3) 	Stone(1.2.1) 	Tef(1.6.3) 	TefUI(1.6.3) 	TefVoucher(1.2.2) 	TefSuite(2.0.3) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.4) 	TKS(1.1.2)
	TefSuite(2.0.4) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.6.3) 	PhDM(1.10.2) 	PhVM(1.6.4) 	Stone(1.2.1) 	Tef(1.6.3) 	TefUI(1.6.3) 	TefVoucher(1.2.2) 	TefSuite(2.0.4) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.5) 	TKS(1.1.2)
	TefSuite(2.0.5) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.4) 	PhAST(9.6.4) 	PhDM(1.10.2) 	PhVM(1.6.5) 	Stone(1.2.1) 	Tef(1.6.4) 	TefUI(1.6.3) 	TefVoucher(1.2.2) 	TefSuite(2.0.5) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.5) 	TKS(1.1.2)
	TefSuite(2.0.6) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.5) 	PhAST(9.6.5) 	PhDM(1.10.2) 	PhVM(1.6.6) 	Stone(1.2.1) 	Tef(1.6.4) 	TefUI(1.6.4) 	TefVoucher(1.2.2) 	TefSuite(2.0.6) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.7) 	TKS(1.1.2)
	TefSuite(2.0.7) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.5) 	PhAST(9.6.6) 	PhDM(1.10.2) 	PhVM(1.6.6) 	Stone(1.2.1) 	Tef(1.6.4) 	TefUI(1.6.4) 	TefVoucher(1.2.2) 	TefSuite(2.0.7) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.7) 	TKS(1.1.2)
	TefSuite(2.1.0) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.0) 	PhAST(9.7.0) 	PhDM(1.10.0) 	PhVM(1.7.0) 	Stone(1.2.0) 	Tef(1.7.0) 	TefUI(1.6.0) 	TefVoucher(1.2.0) 	TefSuite(2.1.0) 	Cielo(1.1.0) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.0) 	Rede(1.0.0)
	TefSuite(2.1.1) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.1) 	PhAST(9.7.1) 	PhDM(1.10.1) 	PhVM(1.7.1) 	Stone(1.2.0) 	Tef(1.7.1) 	TefUI(1.6.1) 	TefVoucher(1.2.1) 	TefSuite(2.1.1) 	Cielo(1.1.1) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.1) 	Rede(1.0.0)
	TefSuite(2.1.2) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.1) 	PhAST(9.7.2) 	PhDM(1.10.1) 	PhVM(1.7.1) 	Stone(1.2.0) 	Tef(1.7.2) 	TefUI(1.6.1) 	TefVoucher(1.2.2) 	TefSuite(2.1.2) 	Cielo(1.1.1) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.1) 	Rede(1.0.1)
	TefSuite(2.1.3) 	Adiq(1.2.1) 	Conductor(1.2.1) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.2) 	PhAST(9.7.3) 	PhDM(1.10.2) 	PhVM(1.7.2) 	Stone(1.2.1) 	Tef(1.7.3) 	TefUI(1.6.2) 	TefVoucher(1.2.3) 	TefSuite(2.1.3) 	Cielo(1.1.2) 	PagSeguro(1.1.1) 	Banese(1.1.1) 	Senff(1.1.1) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	Rede(1.0.2)
	TefSuite(2.1.4) 	Adiq(1.2.1) 	Conductor(1.2.1) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.2) 	PhAST(9.7.4) 	PhDM(1.10.2) 	PhVM(1.7.3) 	Stone(1.2.1) 	Tef(1.7.4) 	TefUI(1.6.2) 	TefVoucher(1.2.3) 	TefSuite(2.1.4) 	Cielo(1.1.2) 	PagSeguro(1.1.1) 	Banese(1.1.1) 	Senff(1.1.1) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	Rede(1.0.2)
	TefSuite(2.1.5) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.7.5) 	PhDM(1.10.2) 	PhVM(1.7.4) 	Stone(1.2.1) 	Tef(1.7.5) 	TefUI(1.6.3) 	TefVoucher(1.2.3) 	TefSuite(2.1.5) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.3) 	TKS(1.1.2) 	Rede(1.0.2)
	TefSuite(2.1.6) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.7.6) 	PhDM(1.10.2) 	PhVM(1.7.5) 	Stone(1.2.1) 	Tef(1.7.6) 	TefUI(1.6.3) 	TefVoucher(1.2.3) 	TefSuite(2.1.5) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.3) 	TKS(1.1.2) 	Rede(1.0.2)
	TefSuite(2.2.0) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.1) 	PhAST(9.8.0) 	PhDM(1.10.1) 	PhVM(1.8.0) 	Stone(1.2.0) 	Tef(1.8.0) 	TefUI(1.7.0) 	TefVoucher(1.2.1) 	TefSuite(2.2.0) 	Cielo(1.1.1) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.1) 	Rede(1.0.0) 	Crefisa(1.0.0)
	TefSuite(2.2.1) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.1) 	PhAST(9.8.1) 	PhDM(1.10.1) 	PhVM(1.8.0) 	Stone(1.2.0) 	Tef(1.8.0) 	TefUI(1.7.0) 	TefVoucher(1.2.1) 	TefSuite(2.2.1) 	Cielo(1.1.1) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.1) 	Rede(1.0.0) 	Crefisa(1.0.0)
	TefSuite(2.2.2) 	Adiq(1.2.0) 	Conductor(1.2.0) 	Fidelidade(1.0.4) 	Global(1.5.0) 	PayStore(1.2.1) 	PhAST(9.8.1) 	PhDM(1.10.1) 	PhVM(1.8.0) 	Stone(1.2.0) 	Tef(1.8.1) 	TefUI(1.7.0) 	TefVoucher(1.2.1) 	TefSuite(2.2.2) 	Cielo(1.1.1) 	PagSeguro(1.1.0) 	Banese(1.1.0) 	Senff(1.1.0) 	Acqio(1.1.0) 	CieloApp(1.0.1) 	Rede(1.0.0) 	Crefisa(1.0.1)
	TefSuite(2.2.3) 	Adiq(1.2.1) 	Conductor(1.2.1) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.2) 	PhAST(9.8.2) 	PhDM(1.10.2) 	PhVM(1.8.1) 	Stone(1.2.1) 	Tef(1.8.2) 	TefUI(1.7.1) 	TefVoucher(1.2.3) 	TefSuite(2.2.3) 	Cielo(1.1.2) 	PagSeguro(1.1.1) 	Banese(1.1.1) 	Senff(1.1.1) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.2.4) 	Adiq(1.2.1) 	Conductor(1.2.1) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.2) 	PhAST(9.8.3) 	PhDM(1.10.2) 	PhVM(1.8.2) 	Stone(1.2.1) 	Tef(1.8.3) 	TefUI(1.7.1) 	TefVoucher(1.2.3) 	TefSuite(2.2.3) 	Cielo(1.1.2) 	PagSeguro(1.1.1) 	Banese(1.1.1) 	Senff(1.1.1) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.2.5) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.8.4) 	PhDM(1.10.2) 	PhVM(1.8.3) 	Stone(1.2.1) 	Tef(1.8.4) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.2.5) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.3) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.2.6) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.8.5) 	PhDM(1.10.2) 	PhVM(1.8.3) 	Stone(1.2.1) 	Tef(1.8.5) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.2.6) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.3) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.2.7) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.8.6) 	PhDM(1.10.2) 	PhVM(1.8.3) 	Stone(1.2.1) 	Tef(1.8.6) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.2.7) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.3) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.2.8) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.8.6) 	PhDM(1.10.2) 	PhVM(1.8.5) 	Stone(1.2.1) 	Tef(1.8.6) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.2.8) 	Cielo(1.1.3) 	PagSeguro(1.1.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.3) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.3.0) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.9.0) 	PhDM(1.10.2) 	PhVM(1.8.3) 	Stone(1.2.1) 	Tef(1.9.0) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.3.0) 	Cielo(1.1.3) 	PagSeguro(1.2.0) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.3.1) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.9.1) 	PhDM(1.10.2) 	PhVM(1.8.4) 	Stone(1.2.1) 	Tef(1.9.1) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.3.1) 	Cielo(1.1.3) 	PagSeguro(1.2.1) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)
	TefSuite(2.3.2) 	Adiq(1.2.1) 	Conductor(1.2.2) 	Fidelidade(1.0.5) 	Global(1.5.1) 	PayStore(1.2.3) 	PhAST(9.9.2) 	PhDM(1.10.2) 	PhVM(1.8.5.1) 	Stone(1.2.1) 	Tef(1.9.2) 	TefUI(1.7.2) 	TefVoucher(1.2.3) 	TefSuite(2.3.2) 	Cielo(1.1.3) 	PagSeguro(1.2.2) 	Banese(1.1.2) 	Senff(1.1.2) 	Acqio(1.1.1) 	CieloApp(1.0.2) 	TKS(1.1.2) 	Rede(1.0.2) 	Crefisa(1.0.2)

# Terminals

	Vx520,Vx680,Vx685,Vx690,s920,d200,pc,c680,m5000,d195

# Enviroments

	PHOEBUS,ADIQ,ADIQ_HOMOLOG,SDK,MONEY,TESTE,CIELO,CERTIFICACAO,CERT_INTERNO,DESENV,PRISMA,PRISMA_CERTIFICACAO,PRISMA_PRUEBAS

# Targets

	adiq,paystore,cielo,tks,acqio,prisma

# Resolutions

	240x320,320x240,320x480

# PC Skins

	D200,S920,D195,Vx520,Vx680,Vx685,Vx690,C680,M5000,TEF

# Languages

	pt_BR,en_US,es_AR

# PhDM Technologies

	5,PC
	37,VX680_PHOEBUS,VX680_VERIFONE,VX680_ADIQ
	49,VX690_PHOEBUS,VX690_VERIFONE,VX690_ADIQ
	50,s920,s920_PAX,s920_CIELO,s920_PRISMA
	51,d200,d200_PAX,d200_CIELO,d200_PRISMA
	52,C680_PHOEBUS,C680_VERIFONE,C680_ADIQ
	49,VX685_PHOEBUS,VX685_VERIFONE,VX685_ADIQ
	Move5000_00016,Move5000_00075,Move5000_00234,Move5000_00218
	54,D195,D195_PAX,D195_CIELO,D195_PRISMA


# System Components

	Vx520
		SO: VPIOS400.zip
		SDK: 3.9.2
		EOSSDK: 2.8.1.0
		EMV: 9.02B

	Vx680
		SO: VPIOS400.zip
		SDK: 3.9.2
		EOSSDK: 2.8.1.0
		EMV: 9.02B

	Vx685
		SO: RIO-03.02.03-load.zip
		SDK: 3.9.2
		EOSSDK: 2.8.1.0
		EMV: 9.02B

	Vx690
		SO: JOEYS-04.04.01-load.zip
		SDK: 3.9.2
		EOSSDK: 2.8.1.0
		EMV: 9.02B

	s920
		SO: prolin-2.4.179.9805R-Brazil_SIG.zip
		FIRMWARE: radio05-V1H.10.30-r69_SIG.fwp
		SDK: 2.8.15
		EMV: bc_prolin_v_150

	d200
		SO: prolin-2.4.149.8102R-Brazil_SIG.zip
		SDK: 2.8.15
		EMV: bc_prolin_v_150

	c680
		SO: TRIC-02.01.01-load.zip
		SDK: 3.9.7
		EOSSDK: 2.12.0.2
		EMV: 9.02B

	m5000
		SO: 05.03.06
		SDK: 11.16.8.PatchB
		EMV: 1.62b13

	d195
		SO: prolin-pelican-2.7.93.9707R-Brazil_SIG.zip
		SDK: 2.8.15
		EMV: bc_prolin_v_150


