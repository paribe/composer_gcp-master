# Process Scheduling With Composer (Airflow)
![Imagemi](./assets/architecture.png)

## About
O projeto consiste em orquestrar uma movimentação de arquivos entre dois buckets no GCS, através do Composer (Airflow gerenciado pela Google Cloud Platform).



# Criação do recurso no GCP

![Imagemi](./assets/image.png)

![Imagemi](./assets/image-1.png)

# Cria Bucket no GCP

![Imagemi](./assets/image-2.png)

![Imagemi](./assets/image-3.png)


# Criado dois Bucket 

um de origem e outro de destino

![Imagemi](./assets/image-4.png)

# DAG criada no GCP

![Imagemi](./assets/image-5.png)

# Objetivo mover dados bucket origem para destino

Bucket origem

![Imagemi](./assets/image-10.png)

Bucket destino

![Imagemi](./assets/image-11.png)

# Após o processamento do Airflow

![Imagemi](./assets/image-12.png)

![Imagemi](./assets/image-13.png)

![Imagemi](./assets/image-14.png)

![Imagemi](./assets/image-15.png)