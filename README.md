This project introduces a chatbot-based crop recommendation system that
leverages transformer models to analyze environmental and climatic factors,
providing accurate crop suggestions. The dataset, sourced from Kaggle, includes
vital agricultural parameters: nitrogen, phosphorus, potassium, temperature,
humidity, pH, and rainfall. These features are integrated and tokenized for
transformer-based models such as BERT, RoBERTa, SBERT, and DistilBERT to
predict optimal crops. Among the models evaluated, RoBERTa emerged as the
best-performing model, achieving an impressive accuracy of 97.5%, demonstrating
its robustness for crop recommendation tasks.The training process utilized
Hugging Face's Trainer API, enabling seamless fine-tuning and evaluation of the
models. This facilitated efficient optimization, ensuring that the models could
accurately predict suitable crops based on input conditions. The results highlight
the potential of transformer models to deliver precise recommendations in
agricultural contexts.To enhance accessibility, a user-friendly chatbot interface was
developed. This interface allows users to input specific conditions, such as nitrogen
levels or temperature, through prompts. The chatbot processes these inputs in real
time and provides tailored crop recommendations, empowering farmers and
agricultural planners with actionable insights for informed decision-making.This
innovative approach showcases the transformative potential of artificial
intelligence in agriculture, addressing challenges like efficient crop selection and
resource optimization. By integrating advanced transformer models with an
intuitive chatbot interface, this project bridges the gap between complex machine
learning techniques and practical agricultural applications, paving the way for
smarter, data-driven farming practices.
