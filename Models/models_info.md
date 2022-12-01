model_1_effect.rds: scaled_charges ~ scaled_age

model_2_effect.rds: scaled_charges ~ scaled_age + (1|smoker)

model_3_effect.rds: scaled_charges ~ scaled_age + scaled_bmi + (1|smoker)

model_4_effect.rds: scaled_charges ~ scaled_age + scaled_bmi + (1|smoker) + (1|region)

model_5_effect.rds: scaled_charges ~ scaled_age + scaled_bmi + children + (1|smoker) + (1|region)

model_6_effect.rds: scaled_charges ~ scaled_age + scaled_bmi + children + sex + (1|smoker) + (1|region)
