
![image](https://github.com/user-attachments/assets/4ccece2e-4294-47bc-ae02-981c6afd3b9b)
![image](https://github.com/user-attachments/assets/23f20e45-58c3-415a-a3c0-5d55d0feb838)


CREATE TABLE `okokbilling` (
    `id` int NOT NULL AUTO_INCREMENT,
    `ref_id` varchar(10) NOT NULL,
    `receiver_identifier` varchar(255) NOT NULL,
    `receiver_name` varchar(255) NOT NULL,
    `author_identifier` varchar(255) NOT NULL,
    `author_name` varchar(255) NOT NULL,
    `society` varchar(255) NOT NULL,
    `society_name` varchar(255) NOT NULL,
    `item` varchar(255) NOT NULL,
    `invoice_value` int NOT NULL,
    `fees_amount` int NOT NULL,
    `status` varchar(50) NOT NULL,
    `notes` LONGTEXT DEFAULT ' ',
    `sent_date` varchar(255) NOT NULL,
    `limit_pay_date` varchar(255) NOT NULL,
    `paid_date` varchar(255) DEFAULT NULL,
    PRIMARY KEY (`id`)
);
