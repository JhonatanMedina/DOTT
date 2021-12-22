pipeline {
	agent any
		stages {
			stage('First') {
				steps {
					sh '''
						echo "Paso prueba de commit"
					'''
				}
			}


			stage('Second') {
				steps {
					sh '''
						echo "Step 2"
					'''
				}
			} 

			stage('Tercero') {
				steps {
					sh '''
						echo "Step Threeee"
					'''
				}
			}
		}
}
